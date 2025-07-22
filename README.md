class Memory {
  final String roomName;
  final String action;
  final DateTime timestamp;

  Memory({required this.roomName, required this.action, required this.timestamp});

  Map<String, dynamic> toMap() {
    return {
      'roomName': roomName,
      'action': action,
      'timestamp': timestamp.toIso8601String(),
    };
  }
}
# kusiAI
