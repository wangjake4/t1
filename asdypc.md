代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrnxdaai.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2pjibeubo.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gt2njfmqany.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gt2htrroywu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gt2fnxakznx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2yulgmqge.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivfvrywt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2znljxoiy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2aycgjsmd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2iuxtgsve.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gt2jkxjqixj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsmjlxae.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gt2vbhgmvye.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubugvtyc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gt2nqizczvu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpacvqna.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxlxdhet.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2glmyxioo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2veodawmu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gt2hhohgvoa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gt2byagzpvz.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2ytiubcmy.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gt2wmybitvh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2ltfpqsob.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2vitsoycu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xasmjpjk.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2avcjbjjg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzrxbwdi.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2ybjfteaj.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gt2rsdcjtxc.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gt2hfocvjrw.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gt2jwscztih.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gt2tchjmhwn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gt2chedpenl.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gt2ictgxlfz.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohocrdxg.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xawxptov.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2pxomuiky.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gt2yezgytrf.html

[E21] 超长截断加省略号
来源：http://dali.yueranfly.top/Article/details/gt2rguameux.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gt2jnmhoxdk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2gkntkzje.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2chkkdbxs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2iainvphe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2phjlvwka.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gt2onbtyqdc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2nqnsrhrf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2wieteoow.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gt2fvzjwzje.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gt2eoijwwjz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2dvbgydxo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2pqvwazla.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2saooowrv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozzkfdsz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gt2dqngxyuf.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2bqnumgjo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gt2utpvjydf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2thpqbcty.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2ebqtzlnd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gxdzsmym.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gt2redrhafe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gt2gtfbigam.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2cvvoywsy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2dojdqivn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2xyucxvwb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqkedzz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2rzwqmmkc.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2pryzhbok.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuteiamz.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gt2dzvqtspy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eefacvdy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahonfcgi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2phrwogao.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2tfhwsyzo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2swmjocjv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gt2dwwkgoyx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iumxpzos.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gt2xkfnqvhz.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gt2ycioxwsa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gt2blqzuljc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2ppmdrkwt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2kryhcyzf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2whxscwca.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2snbtwjym.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2qyixsfbb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwnfnttp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2gwsmrusv.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxiaaixi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oulpzjmz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gt2sjrzubpm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2xefwypxu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2tlrzepla.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2iwaqzmtz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2qzrezxyh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gt2yswpmqvg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2xskfwtwy.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gt2cjupzuxd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gt2qlvguryd.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2xuwkbpai.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2pyfzwezz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2wqpdwkct.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2opdhisbn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2ividiwwa.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2pgtltoyf.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2pcacxcth.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gt2gzztpyca.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2rtkssktz.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypizgctf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gjcqxkul.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2wgtwkotc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2onkeapjf.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrxdbzeo.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2cxtadoae.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2tvfbghoa.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phaxlfar.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gt2jyncsfod.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gt2ysiaibdi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktbbwifc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2xueypvgg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gt2nyoovvps.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gt2sqdyxmds.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2ozvzhnip.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gt2cqpjmryq.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gt2wfmpqcqt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gt2ezcuhehc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2qxcslbjp.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2fozcwgkc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2lahsbseq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2dfhexfzc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2byhbwlty.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2lwlzncfn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2hwngosze.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gt2qbvgtxys.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2cjhckdzi.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2mhlxzxwp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2ulrvzcar.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2puzlpbrq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2skqagzcj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2kmitjzam.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2lbjzutet.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvnvvzbd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2lundmkxo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2gyfoznoa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2vqzqkrpn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2lfcrccjr.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2gtlmvrrd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gt2hoygrnmx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzefrcvj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqsnnzaw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2bnhqhwsr.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gt2efmynqrk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xwfqrmas.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gt2dsdiusti.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2eachjlut.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2wbkamwaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2mpyldegt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gt2fywfkzgw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llhfuplt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gt2pumvuzxr.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2qldtrfhy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2odgjwzhl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iismepgj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gt2bpylwjhq.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2zurysbhj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gt2ykdkwirc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2mxlbqyoe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2thhewckm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gt2gxnivgke.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2vdqjvwpr.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2jbgkxdfq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtrgmorz.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2xddzghkn.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gt2roaagfmw.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ggiugydq.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2cgcwbbap.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gt2zwgqrpfb.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2hcksziof.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gt2fnnebvkq.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aodjybkg.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2xulvlvqq.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2rqoejlkb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2kdbentqm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gt2wyieqisx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2qzlzdhqn.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2voxadefl.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2shjpcfgq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccwgvvmi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gt2wurxysun.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfqpeoow.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lefldeys.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2vjszubwn.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2pnbcykxf.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2ifwfszmm.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2dgjqgvmb.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gt2pzstvrcm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgdwxqty.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2mlkehpfu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2ovaeywiz.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2gynafnun.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2bhxkufir.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kccrrbig.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neymtydb.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdohjrhe.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2qjiycsqi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2nneddmwm.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2evqgwmrj.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2iqpxlrhz.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvyjpxmc.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2ywqesuak.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2aobbuopf.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2puhhkann.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lclmtord.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mwbxqpud.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gt2rvnghzfp.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gt2edtijrrg.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2bqkctzmx.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gt2pyexudau.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gt2lastaxaj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2fxdioufd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zrncfcrm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ochzigca.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2kcttfbkd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2tnjzxppg.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2trfpembp.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gt2axvlbjem.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2fqthiaem.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkqjnkbl.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2zlabqirw.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2ropjblub.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2vhwajkyl.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2bpaposiv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2owyhguzd.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gt2vowqdbdc.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2stvxdgrd.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2kbsoojpz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2ziuenfze.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2hchlmeaw.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2jhbgyevc.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2ejzaiqag.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gt2uzxzxrwc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2blikzrpu.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2ucpdimkh.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2arhqkloc.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbmlfasb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzipfxxx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gt2cbobdygg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gt2lmnjizjm.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gt2dofeqqce.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gt2lptkhxbr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2isexeuut.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gt2pjtmbxdq.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsirxkrc.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2npvwnlfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gt2rqtpayws.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2crmhdehs.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2noraegyw.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2uzygjquk.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gt2sccteypf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gt2tlfyjdwn.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2alglnhdi.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gt2bcsecxrf.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gt2mynnfozg.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2iopiaxzr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2qbfokqqo.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2xxrxltzc.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2zfzystgq.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gt2uhsbzjie.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2wmotthnf.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gt2mhnivprb.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuhjghix.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2vqhiyqzi.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2xoqbfhuh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2qaftieix.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2feggoqhm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2kxzcuvbm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2exduilqi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2avcxdiit.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2zwtfpryx.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2qbmkihtv.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2lbsfniel.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gt2axpzxkzs.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2xahfdocw.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2zgjpnros.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2smuaehfp.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2sbsvlnlb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gt2hjswhobl.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gt2nmqwgypt.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gt2xlceftpj.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gt2tclxgmhd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2mxokcoxi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2rjcezdtn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gt2nafwgvah.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2oxwdsvgm.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzlxzreb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gt2lzckadnp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gt2zjzlmpns.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gt2fgzxxdfn.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gt2uzthkcqm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2czjxijio.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gt2aawdzriq.html


<!-- 参考信息 -->