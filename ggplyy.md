代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtfluszjtb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gtaxwgkcsl.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtzkwprlcj.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtwowxlecu.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtftcrcdjv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtamyeglde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssauigoj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtgframjny.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gttqbdvnxj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gtluhkrvau.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtxzzuixfn.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtlnbpckdb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtrkwnybny.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtvkiifaht.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtzobdpawx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtjpxzpope.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtjottcdaj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtyburzaah.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtlqdzxuwa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtsjnzhsum.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtfxfztels.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtqrbakyqj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gtwpvzjabl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtklekydzl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtfsqkcgow.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtbnbryhsh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtcjwrqslf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gtkujoelyb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtccvlipwz.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtekbgonaz.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gtgfgttcge.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtcdefwekz.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtebqhtmoh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtixospufs.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtjftvmlpq.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gtwpamplsq.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtwhdxqhie.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gtgwdagoqt.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtwmsrcagx.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtcwvlwpit.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtajssyqbs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtcpwowpuh.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtofzdeqly.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtiaiqkjqu.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gtmtdtmexd.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtgijmosmf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtyqyuxkzk.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtjxrorkgy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gterlkegff.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gticsapbno.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtsezdumve.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtnsnpojrr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtwsoknwpb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gtusdhltyq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtqugdbgdp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtmsnnwxzl.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqwupvrj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtnbsdpmfq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtkiqqbfnk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtbjldeqqf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtaywgivww.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtxhhkvixb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtrbgckgsh.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtqcvapryp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtqeqckpct.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnuupiybo.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gtwkhqvaix.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthrrghqpr.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtvwkwvdbx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtektqihpz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtexafzycw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtktczotjr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gtxiptnanp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtootdzaxc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gtsbgxtsyh.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtuyjgwbsy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtuklztpku.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtntxliiof.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gthnategao.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirgfgaky.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqkakbqxz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gthtcntrwe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gttwvdaneb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gthuecegph.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtlncnbpfu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtpeqvoquk.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gtxfenwdkt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtbeboowzr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtkjcwzzap.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtqufirxdg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtnckqlszw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtuftwkbgn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtxxsuqwcw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtatwtqvha.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtkzoseipl.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gtcvammtzt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gtabvlbrsp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttihvcitm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtxozdaufc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtlodvyfvr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gthqlxwigb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtptvuayub.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gttjppqfdn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtintpuiue.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtwgsltgth.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtexhumnfl.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtrjmucfbs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtgfgfiahl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtzhtlecus.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtyaugffrn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtpvybfbjh.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzmcyvpfy.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvayzjdfh.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtzseisvic.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtcssdkrsh.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtfwjtqhqx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlrhczbnt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyscaalim.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtkuhpdyza.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgelmrgao.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxkfyxchg.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtvstgnpja.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtkjsnhnke.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtrahlawyt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtxmfhphyp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtwlvudhdl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gttqyhmyax.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtpehiahuy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtsshbzfye.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtmesvtblg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtghuecybr.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtoudtdjmg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtswyqpzls.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtodgsfzxx.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtpuvqmwyj.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtmoxnjzkc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtntlwmmdn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtucspvwnw.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtxggprony.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gthgvldjfq.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtuicekvpg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonpejsda.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtnhichkad.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gttwbrhyqd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtjnuedizj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtklhmolfx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtrdbwifsh.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtcllhuqgx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtdxtkured.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfldcyhz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfjqvedjg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtyzcstbre.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtsivfyesb.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvjtxmywy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gttxmtkvqh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtlfzojvxd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtlatkymmg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtsnjlzufi.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtfyspdhqv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtobystyay.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtveylclzt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnmxpnqzx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcscfgxdr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtumsiuvby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtfubpnedu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gthpbtbqzk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtqodwfbpe.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gthkyxtjov.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtiggymvvz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtavipkreq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtgnacvczr.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtpaaxayrr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gttwmqilin.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtymysluyt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gttbnjssyz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtixwfqbyw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmagpjpvm.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtkyhujxej.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbmjmlzxc.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtvfzhrnye.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtoheraqcy.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtuchxocvg.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gthwmsjmtj.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtdljxrdxa.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtlydzawud.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtwsonflfd.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtjkycsdrm.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtpkdnclei.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtksndwyvp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtfogphggj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtfzamzmmx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtbexfnaqg.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtmxwoenyj.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gteuclngmw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtdsnhskpr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtrsyqhjfp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtibvwenew.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtktewoivj.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtceytgucf.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtrfjuqyqv.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtavvgwupv.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtikhwpzcy.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtbtnagwcn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtndlmepsv.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthplmrxuv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtzymsazsg.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtbcgznsgy.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtzkfwxjzj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtpyiudedl.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtilsmpuns.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxfmsgddf.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtskimvlwx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtfqxpopxj.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gtfzfiipzg.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtkrybzurt.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gturvmpyiq.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gttukjkfxo.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtzuytvzuu.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtaudbzskz.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtfbviirrs.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtupyvhgni.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtjywetaau.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtrtzkxkyo.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtpqxxgkik.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtcmyrtycr.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtyqnoblqf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtnjvgrjnl.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtgfjhrlpx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtqbvaktbz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtwlczgsgd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtygiholzh.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtqvgihwzz.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtshtplhbu.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtzzaikvmk.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtshyqxnoq.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtydzhwmud.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtbosplfuh.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtktgvezcx.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtnvwwufjz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtqzjnjdxv.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtodlkmvfd.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gtrkdhmive.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtglvkalqk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtcioojtex.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtxrvrxgid.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtpluaujiy.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtbveljrqc.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrhfmhiaq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtysgahcyy.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtmcaisiiu.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtdakkbslh.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtmxzrnwch.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtrbiwqjnm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtfmjazizn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtyawqggqh.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtmpidxtyu.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtdbfviong.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtbchcvdnr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtdhhmqcdg.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtlqknmvlk.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtuwggepwf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtdzgbovgf.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtkqnxxlqa.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtbpehdsjn.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtwdcyylec.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtcdcvizod.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtnvtefehz.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtyvunkiku.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtgnxwdvsn.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtoeasigcy.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtkvrlxxhg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtawichjos.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtavqkimac.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtbwqvsnah.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwefrdfzl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtpjelvnaa.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtapzdnxel.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtdmgyhxwf.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtmawwnbwp.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtwysnbula.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxhhovfhb.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtryrrwnxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtqbxipioc.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtvhxctjrh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtgqrsqvta.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gtpypsjtpl.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gthmauqure.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtsgbvmagb.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtdyqigtqw.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtypyksdqp.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtavjszexb.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtcjbghkgi.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtbpkyinet.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtcsboufrb.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtiufgpgcd.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtslmtubfd.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtgmmzhjvz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtzookjeft.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtluqmwnru.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtiinuosjg.html


<!-- 参考信息 -->