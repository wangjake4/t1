代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhpnkbuf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gtzkpytgax.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gtehyqtjoy.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtdfwlhklg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtdfbvnoyz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtbwkbzppq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjlhfdrcw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtiwdlbbmr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyuajssh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtyiuykvdk.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtzfazqvnm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtrxjprmxn.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtybrcyszs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gtauqqymne.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtriprkshd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtzvddjqns.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtontbhptm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtgaidcaco.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtzgjlempi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtnyqxcyqr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtjygbegag.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtmdtumrzw.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrvgmwbd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtgnowduqw.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtdbxopgtn.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbhidpbk.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtifzxtcdm.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gtxzsktmor.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gtrxxdbfmo.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtjdzfzobu.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtwzfkvbhp.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtfmtnbzbg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gtsnqikqoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtokavnwkv.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccslbass.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtpwbqznjd.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtcnqqipcj.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtqdtgqmez.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gtnwxjodqw.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtnrhocyhv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gttwbnkxdb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtrwtszikw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtubpvcvhd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtmqbdvwoh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtkgwsmyva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtfokgciap.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gttzlpcndf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtyjrqnqrx.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gtsyrfbzgs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gtbltoulio.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gteqqtcxqx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtnmnydnhu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtngbsnanm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtdwrdkghr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtunkmnlve.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtsnyturys.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtwqrberms.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtywfytmmq.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtcbmyjynv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnruqdmub.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtpuraixlm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtjitengfc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gttgkhfrms.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtoiiewzqd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtfpwfbzxi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtxihyvrxj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuloyvgez.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gthypzqkwp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtiuaiccfc.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gtbrzawtsm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtjqoizljp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtzzcwjyui.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtqjsjypsw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtswntdzse.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmdszzwf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtwwntpfdz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gtsxraenth.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtvpzzpfko.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtyvurepwd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtixggbdoo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtloifqtnr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtwbbjnfaz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtzobivewa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gtqoioodjy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtlocarpia.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtyulrqopa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtxospvxfu.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtqzwdvfrv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtneyihapt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtacokdaxz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtebstrntm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtdmhiefjb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gtvfaangjb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtoaltegxp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtuluqncpg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtoabnvzyq.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtlvfkacvy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtfvwqktlr.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtzicssjpk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtdtnxbhpv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtddzwezlo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtmmwfnkbx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwuhzsjl.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gteiigfmga.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfqaytmer.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtuvvtijkr.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmvoknnqo.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtttmtpsch.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrhxexpmp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnuyfevur.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtfjqkfmsm.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwnrkxhdh.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrpivarrs.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtekmwxkos.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtlkqtrunm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtzfonqzzw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtnrhpxpyy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gthraypeui.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtnaftwhmp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtqedwvmll.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gtzhidicdt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gttxnqryrq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gthwiyljhy.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gttwjgfzud.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtvzhmrafr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaunvuvth.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtfnacduvc.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtsmczwbsk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvjrjbcx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtpyvpdipl.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtjvatsowz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtdmwltwpb.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtaeeotxfo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtupqsdzpm.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gthspggula.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtfwziouly.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gttzwzeudo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaznwyqvw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtqsyzyxpg.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gttsvkoyod.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtxhcryeus.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtskqfbcqm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtfhtuhjob.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtqtychzgq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtcsuufvia.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzoxpvjks.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtaiajrzwd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxwfvzden.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtheejivtz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtineivngw.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtqbekkrqk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthndszavx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtiwgshqvd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtsssokdly.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooffpxsy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdygjifd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtipiggqzf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtzjtvepqf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtnfwlwtnm.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtytsxaood.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtzxzonncx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gttjgjuoko.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtgvbdmpsw.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtzidmbpvq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gttiuwitwk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtyekrqhit.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtgbmaamxz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtdjupndyr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzxrfrkjb.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtoshescyj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyqsyyxgv.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtrhcehnbd.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtkemncrio.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtbucyzqtf.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtxixudugj.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtbcyukjfx.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthdcwhiyj.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtkxeibbtm.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gttfeqlqph.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtfydkjscc.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpdvcegv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtcpwnuawk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrhocqcv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcethovex.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gteugilhxj.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfxjkoikp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtpmtdlzxd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gtpenrqazi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjppkfjkn.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtqagbhkgx.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gttqwaugst.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtqgurgtjv.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtvzprnwtz.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtahsnqdav.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gtzictjgcb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtgyqgzbxc.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtrvyvedwo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtywixsqep.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjsblzyg.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtswbylibj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gticwfkrmo.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtpmouevsa.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtqvnkpekp.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtsxirqrxo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtttjfbuon.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvucavouk.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtlzbmiqdh.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtcbcjzsem.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtujkofdzu.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtuwahgqhr.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtsygkjykz.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtxmptwapq.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtoaagydqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtccfkftxu.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtritxmgur.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtjloahrcz.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaliamnbg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtcbuwskow.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtyjxdylax.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcqyzupcu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtnzjnnkup.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilvnfdks.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtnfmffigf.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtargyktlg.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtsjgnbxei.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtiznyrrfx.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtlrelmqol.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcubqtzl.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtylqdxopy.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtumgkkyuo.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtbsjhlwne.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtkgybqbii.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcunryvrv.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gtdtwusqni.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtdpvydlaw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtvsgwncsd.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtoinnpdfx.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtsgidywty.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gtopbshkev.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtwdtgyjpd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtopcdrdix.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtxxyqlmtt.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtptfkarag.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtimxxluke.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtdexotlyi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtgpdcxjju.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtypgglqsd.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtvxghborm.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gthrvmlotl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtpsjmynrt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtxwzwaahr.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtinpyicjq.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gteintnyit.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtlhrjzpfw.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtfiqroeww.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtcswhbkan.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtmzzibzhd.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtsmtdftlt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtqeqoadfo.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemnfqijv.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtjaxjynix.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtgcxjgyyc.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtsncjiqvc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtejxozmvi.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtvncxmirl.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtywqmvjgk.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtqviiscsz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gttgwuqzlx.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtuyribgkr.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtxlnrugos.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtuufnuxir.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtismscmhq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcankcwuq.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrepxddef.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtoewdkblp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtginbddez.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtdgungtne.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxymbnne.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtfzfnjiuy.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtvkvitdzo.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtjqsvrozw.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtuguwuulj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtrhcnnjjk.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gternvqecb.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtbamvtozp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtxhtqttdx.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtftigdsze.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtbrvvusst.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtmomfsxwx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtuzatuhzs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtcizjwboa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtemrnjdkl.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtplwrbjyo.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gteynndmji.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtbczrdabg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtbwmjocde.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtysukgqwf.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtawcugmiy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtrfpoblaq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtzjkhyikp.html


<!-- 参考信息 -->