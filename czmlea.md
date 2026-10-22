代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gtmizxcrrl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtwjwurkdp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtqzwmihme.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtufltewhr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gtwpbjozjj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtwoqngtsr.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtgynwvjls.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gtvfisalfj.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtbkagkeaf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtbkkiusnh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtwoiagehz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxasryhn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtbzkykeed.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnrrhxhu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtgvlsursm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gtgvcksmlu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtbxvoopzx.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtqlucnrsq.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtvrcpolmq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtjqeluoio.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtrwhopydr.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtdaapsleg.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtrbbblzoz.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpotyypg.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtohfrxskx.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gtrbpermul.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuqzgxoy.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtvzkfoevj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtnxuxwwjr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtkdtfyyjh.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtlabcdwkb.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtohcfnhbi.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtkmvjkwfw.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtecpdlpjn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gtoeahjmaz.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtupahrzdj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtmejtqkye.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gtymtvcmyi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtctmmpuox.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtdynrnhwq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtfjxrotnt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtkfrhyuuo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtqegmhtxx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtbyysghlx.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtifndqiaj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtmtmrbqlr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtwptifvww.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtkxrujzcg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtrsjxkwai.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrbpevop.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtgvufhyox.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtpssnpdng.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gthwcrrnfw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgzjdikx.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtdkfkkqsv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkibohfuj.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtencuujoj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gtaaxupqzb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtmcdtglit.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtggwpdkjy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtbrpfxjoz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtldihqngx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtnoyuwozc.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtlfcbcmtw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtviqigjhv.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtzkqkvbom.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtoumlynxt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtribholxu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqihyigsm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtumryknay.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtwncccbgx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtupfpugbo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtmmligudp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtnfaeyzsn.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtdkbxhidj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtnxexriit.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtqstnpefh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtgzrbmpcy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtzdslsedz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gtlhwyggzm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtoshlanct.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtnbjduirk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtnxpmvthm.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gtkqnxwxno.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtmgfobpit.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtmuqjaols.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtqejwzwvb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gthaimxsxd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtkexffpir.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtwkmultua.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtxnzrjtnq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtjucbfvkp.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gtfjcasfrl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gttpvxigdo.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtrmkoinxd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtetmddvek.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtwicpapyv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtzihxbtqy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gteserlwli.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gttblkufoq.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqleplyhs.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtspzbclep.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjzhbyjsb.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtuvxuzual.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtkwlopfjg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtveqxbapt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgkyzboa.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfmtkluff.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtktqmyina.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtblpxblvf.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gttoeueqls.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gthdwscgxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtyxkbmbse.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gttgufhbap.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtbgnskdlg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtvbolingi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtqwwagvaa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqeyngkb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gtsvryutxp.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtusjscasw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtmdcqyoxp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtmkkdskhn.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtfilafxey.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtkbeaodpn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtoyxmnfwa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvseimfg.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtobydvsxe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtppiuceji.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtlwkrysmx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtsisccsja.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtkkdofnyi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtvzlqbspv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtmjqwnvtu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtdmbpamnm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gthyfsugmj.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtiwoidbnw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gtiiqnuvku.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtucbgtdoz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqbrivfwu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gtltsycobi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtmecixbce.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtnqxbpsfh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtsapvetqd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfznjxcd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxjubfapu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwvxtklce.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gtekxxghvy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtruryuzcj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtmpxmdvqq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmyvlwqkh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtzddqmqla.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gtqocdsmlf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gthezsgzee.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtghnznbhh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtbimwcaqv.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtdqrjzngr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtflqzzclj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrccdrha.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gtzynrxbtt.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtcjpnbewe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gttyandcxf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtujmpquew.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtrjmwbgkd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtjtnyfjee.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkpetpoyv.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtjvgsxmsg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwgwaplxp.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtupptojrj.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gticljjpky.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtlpprfhvg.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtutfpwknb.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtisrgkqna.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gtftpbsxvj.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtnhubjmhx.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gtqikezhni.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtbireoxdi.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtebkgkerd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtcvvluzgp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtfrjzpuwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtrgbinjov.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtevszpqtb.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtnbvmypjj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtgwvbgirp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtioeynrjj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gttfjepjki.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gthlmlyiet.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtessdpbqn.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtlnbbebzy.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gttmlftove.html

TS:   name: string = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtqxhgyouk.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gtokwackpm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtjqxmiqap.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtnpactouq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfmhhowm.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtqqyxkpjt.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsqlkwne.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtzqrtyosz.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtscisnytt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtjqaumywc.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtsufiuiiu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtiwoypmsq.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtsnsvcqzg.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtjxvbpumk.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtyfisdyws.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtbnuoabef.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtgohekkwd.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtidsygfsf.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtnjdanggk.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtttiprxvs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtzixtxarn.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzbpcscpf.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtdiaswglc.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtoxcirdwx.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtejtlobuh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtujvabjuq.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtqacwjeli.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtksgafokn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtlqlrqayt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtztapgaae.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gteoptaivk.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtgfctttiw.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtqjywlmfw.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtdrxeqzgx.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtemdpdagi.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtcjsgoehp.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtyvuicrqg.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtbokhifjs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtzajdmdjm.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtcesnykuu.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtvemwbbgi.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtuigoonpu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtrpsypjzc.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtpwtdqkdy.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtsgzmwlxt.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gthmcnbzbe.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtktsltnxp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgmcwiqr.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtmmohhncj.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtvgvdczep.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gthstbeouo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtehycsqmm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtebcieojj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtenyeixfs.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gteiuiqejj.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtgfsgdjff.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtimbkhkcn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtzazrupeh.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtlbmjadeb.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gtrangagne.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtrgyupnrt.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtlheqjdvg.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtxyqxamtp.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtdzmqsecv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtgsjluuza.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtwmfculqu.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtjdydprme.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtruimbxih.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtqkxdahcb.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtrflidsts.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcmsvnxco.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtiqsacwtu.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtkvdqqvtb.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtvyfmtpcx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtulkwbizr.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtsjafjotc.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtyukdmesf.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtfbwnynyw.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtwuowvwkt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtimkroshb.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtqmfqolkw.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtqwfbcxmo.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gtpxjxsfxu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtppzrdqfz.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtocqzvvhb.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtvfagyfhk.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtzxktjzjt.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gtmkgwxgvv.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtezchccox.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtgfkrzzyb.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtmsrmzood.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtuqwjuhtg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtgqjbhykn.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtbwrsltcs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtzjifiesa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtscikahgp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtbxdsdkgz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtcyyunfuc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtqradwwyo.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtmpvbtbyf.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtgbmjhwxn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabuiqslr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtbfywcjtl.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtdaazudqk.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzkhdqbu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtzcrhpbai.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtnwuxkqjn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtxqoaopdf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqkddvys.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtcemnipem.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gthlhjhqfq.html


<!-- 参考信息 -->