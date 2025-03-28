# Operating System Project

The AI-Powered Directory Management System uses a multi-phase, structured process to automate file organization. To ensure traceability, the system starts by setting up a logging mechanism to record every operation with timestamps. After that, it searches the designated target directory (such as the Downloads folder) and, if none already exists, creates predefined category folders (Documents, Images, Music, etc.). Every file is examined using a hybrid method while it is being processed. The system first compares the file extension (for example,.pdf → Documents) to a predefined rule-based categorization dictionary. The system uses AI-powered content analysis (future implementation) for files with unknown extensions, using image recognition for media files and natural language processing (NLP) for text files. If classification isn't possible, the system falls back to the "Other" category. The system adds numerical suffixes to duplicates in an intelligent manner.and maintains the original file permissions while moving. Every operation is recorded with information such as timestamps, error messages, and file sizes (in a format that is readable by humans). Upon completion, the system produces a thorough summary report that includes statistics such as the total number of files processed, moved, and any file types that were not recognized. Future versions will include more sophisticated features like real-time monitoring, cloud synchronization, and scheduled runs. The entire process is scalable and reliable for both personal and business use, maintaining OS-level security by adhering to file permissions and using effective memory management for large directories.
