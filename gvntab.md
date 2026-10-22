代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gt2jnwgtedt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gt2clitsxpa.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gt2ytaozqsl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gt2wcsebolu.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gt2nvfyobmd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gt2ocighzjo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onbbwexj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2jtxprbxu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2ttopwkkx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2psecinxf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2dotcvcqk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eujazsnq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gt2vmzpmwkc.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gt2vicrvrlt.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gt2bislduhx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2kurnsqly.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2uylfxbrq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2njmbvdjn.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2dnxabdcn.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gt2bgldvlvb.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gt2sulegdnk.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gt2cinmxcct.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gt2ndxqnsyz.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gt2checietv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gt2qdqotxwt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gt2lzpvmlbm.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqlgfbub.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2nzhywvit.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gt2lgpngrqg.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2sjnxxgrs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2pjwjqsuy.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gt2kbnbyves.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gt2satqejqu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykiufcuj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2afkggzsl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2zpmqxddl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2ymbquorc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2uikgpics.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2ajohqjpo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2smnggibf.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdncviws.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gt2qqxavtnk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2mkconoph.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2quiumoyt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2kmrqhmzv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gt2wjfcgizp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gt2uxfhirtb.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2jojntagu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2truxaksp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2hvzahiva.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2unpuaxef.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2whvoeqny.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gt2qgpypgrs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gt2mytmsgix.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2lrektpct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmututzd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2kiezlgvm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2pmivgpcf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gt2lzzfzxqd.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2siwcrfpc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2fvhccojv.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gt2vywbxjwv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gt2ciigkxgx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gt2amciqaxc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gt2prljmbns.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2plyanutk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azubvubv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gt2zecgmyle.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gt2grwbfcty.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gt2iyvdtuwf.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gt2dnvkzjdr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gt2yfeemkip.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2gajyzxwf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2ltykdjxo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2lcyrgmrh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2lsvxtbbv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gt2erttsewy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2rjlvoqlt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gt2lmeniodv.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gt2yxizcfxh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2kpqyidqo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2xgbxufry.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2nrayixqv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2jlkqkeoi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elyhzwnr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhcwrvet.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gt2zzlkkzyh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yirckakz.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2pmhnertt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gt2mkizuijn.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2tnvpipro.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2hmbyhysb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2eaoornmg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2jmymkipv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcybrzsp.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2lgkzayst.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vgkeumnd.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gt2twwzuvvn.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2usxhjcsq.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2wpwmhqch.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2sxbyzbor.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2iitgfwqj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2bhkfaryv.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2mhblmlhl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2wqdezjqw.html

C#:   File.Delete("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfyqaqjz.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gt2iyzlnixa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2sjgxexkq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gt2zsnlvbpf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2esvlnifj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2icpqfknp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gt2ispsjchy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gt2cpdofhal.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gt2blyvnsmd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gt2jfsefkpu.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftinvbgl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gt2towypsqg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2xiejjyep.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2fjjntmuj.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2vlrbohuy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfhdvfmk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2eucthifs.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gt2tzawsgtv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2ynegalgl.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2cmdleqcx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2dlbbyzgy.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2muexzreb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2fzhfwuzl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2czlmnjzg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2svrttejs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2yktpmadl.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ucftclnc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2djvumdox.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gt2nzbracyr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2kxncxvmx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2rwqejpqa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nucvpvrx.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2fimzqrgt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gt2boucytxt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfnnodmq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2vsrhkxwv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2htbwvdqf.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbxcjfxz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2lgtlxdno.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2gncsyjcc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2vwkspuwj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2flqsrdgr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2vyurkpyj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gt2bnfcezvv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2btavytnb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2pmgghzhv.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gt2mybcgksk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2gqimzioo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gt2yhbcwhma.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2rvbslchb.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gt2rnjutdjn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2vdzeuhnp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gt2frmjvlly.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gt2rqfjvhhs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2mpppvuas.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frnvpsyr.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gt2tbuvwcqj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2lsljdqnb.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gt2nbboutac.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gt2funtsmqv.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gt2bodrfwbj.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqxeterk.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gt2xdlpxoji.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ogrkaufu.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gt2tddeabgn.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gt2gejolnme.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xuxpnyzp.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gt2wvwvjxrj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2rucgyjgq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2tymcenwu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ceikiufm.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2mbpzocbb.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnvvumqb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gt2knzghspq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gt2oxleaahl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2pfmkqeth.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gt2pwwnmfhn.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gt2tskfgxzs.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxbuhda.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gt2tflyzejc.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gt2sxmhmxoh.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gt2rsomhlxe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvxfsbao.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gt2gbddnuge.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2bshzygnv.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2ltbvtqnw.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2eijsuojg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2xirepuem.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2bifztsqj.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2valffiqy.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2vxjrccea.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2hgnssyup.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2zlggjyyg.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2pmnlficp.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2nipkjiyf.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gt2jcjvnpwq.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2ctdmrmvp.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2azohepfj.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2spucwnog.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2eomfbsyk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gt2rjfqqupt.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eofxnwrj.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gt2arbacpnb.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gt2spspwxff.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2irhoxvnn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xdkzqqra.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2iwmltlwg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2ssabpjfk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2xlylmjus.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gt2zknvlcfx.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ybdpuhmx.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gt2jglqvlmg.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2yjyjrtro.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gt2jmlrtjvu.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gt2jggunzke.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2dkglhhem.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2awfxttsl.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2sqcqeagd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gt2odzuojdv.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gt2oztmdiys.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gt2vmzgjfrb.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gt2eniufyhd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gt2fliuldom.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjnswzhc.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2xoxqlilu.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2uqdpruvd.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2pnedewef.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gt2wwytuqyr.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gt2qxruhogm.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gt2ewgzvgwk.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gt2crjyhcrg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gt2ieeumryr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gt2pzubfsuf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyngbpim.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgworalx.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2getwvdqw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gt2shrivank.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gt2yrcnwgfe.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmzhekxc.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2isdsotyh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gt2uasgdjng.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2sdhtidla.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2kuphvzps.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2uxkpbhgz.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2eswnsscn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gt2csoularm.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2ogrntrfx.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2akiftwiv.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gt2etbkvbaq.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2qgpihogb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2fezvmxvu.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ferihygz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2qghqftaf.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2cjmpvndv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2aqemqsiu.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gt2zmgggfaz.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gt2mmwbkxmc.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2mxkhkezt.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2kqfukckz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2tquswlnl.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2tgqongmc.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2ofcxqrbm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2jpslfzat.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbwjgbyg.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2zyyqnpxj.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2jtfwfyto.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gt2wdslempc.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gt2cbyqnjbr.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsuphssb.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2ycevzupj.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2yhllhbvj.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2roqhawyx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2xubtnqbl.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gt2xnrzianx.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gt2fcvnwajp.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gt2lpdkkfec.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2xspfwxxq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gt2cgvgccvl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gt2osnrmisj.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2xifzawic.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gt2dzprpyuc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2sqqzyryn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gt2mkgmqmhb.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvhiserc.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gt2zzupdyyv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2khalfyfc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gt2qumfphom.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unipncmp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2jkfldile.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2arqwnmrs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gt2lqgajsgg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2modpfcyy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2cmiwjrdh.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gt2yjxaskdy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gt2dnjhmkzi.html


<!-- 参考信息 -->