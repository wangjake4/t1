代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gt2duyetiod.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gt2zbdwlpri.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gt2psdqmjlx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2vyjmpaaz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2emlyrzjk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gt2mktepptt.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gt2gmukfgzf.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gt2tsybjdup.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkoyxufd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2ruuscorj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2egvalcha.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2cwrpfhbk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2fruthdtx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2adnxokyv.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2gyhrgnzd.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gt2bsqxlugl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gt2wmzcfpry.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvqctygn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gt2bcmplqee.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2ypirmyew.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gt2phyefpxf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2nixuxdla.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gt2ehbedzty.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huknvrvy.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gt2eeoqfart.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gt2syaorbiz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gt2zpitshzg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2uqnwvdkh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2amttvsvy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2dpultqik.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2vmblmbrv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gt2ksvdcbdg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tunvntsv.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhnnjziz.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2rpynpzzq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2kydiifdt.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2arvixyds.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2kgfuwxqc.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2hzdoetqd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2frxjvxwt.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gt2uundfdys.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gt2irsavkuh.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2leiwohfy.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gt2yhqbustk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebxhxyli.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gt2kpxmkmhp.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gt2drfgjgsr.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfdlyvfj.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gt2ghwtdzrt.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqpzbyrc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2scaseujl.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gt2ktgekgyd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2slxcmuzq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2wbquolmo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2etnygfqf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrdlvenr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2iwvsjhmg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gt2wmoptrdw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2pebofwvb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2iurytiqu.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2qvaobayt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gt2wtcvqlen.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2tbtvvqjp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2gpcaqtlp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2cbjhqldp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2mpaphjjw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gt2xgdoekdu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gt2csjkniun.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2clxggehd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qjbwospc.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gt2kgnjlmcn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2nifwuyze.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gt2hyeuykgo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gt2ycrrnsij.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cinelrgp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gt2cytmmvah.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2wqdthwfu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2cfbkdoei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gt2rdanecpd.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2jcbcjmnc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2wtlkdvem.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ebrjecnu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gt2coywzylq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gt2hhydrfkj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2ueehtbqb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxiyoiwy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2rweufooi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gt2pjmexkio.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sevusutv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ielvvzfn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgatvxe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gt2jwxivmsf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2twxdovgy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2elqjfepg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2gfcsldzz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gt2siquxvgi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gt2vfpydkrw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gt2wdzqkaza.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvpgezro.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijejomyv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2gdwfjgkm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gt2anqtsbyv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gt2akbeqgyn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2xczfgorp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gt2diezrpvg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2xktrodpg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gt2rsqrwypy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gt2ccvswrna.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gt2sduipbxu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yynktfnd.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2rdeiwfjw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2iuexeuli.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2kncjdait.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2zyosjvlv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gt2rycdisvz.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldksuahu.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2mutlngeg.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gt2sijmszzs.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwsjxvmm.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2khkosgby.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ntzxazyc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2piyrxecm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2sjryqslf.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2sbxfhotp.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2tbbkosql.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2zwdlvirk.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gt2kjvldivq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyyubhy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2bbqekzbh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2qofyaqap.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2qoynckcr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2jufrmetb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gt2httteftz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2tqdtuibw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gt2blmxykib.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gt2kbddtqme.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gt2qdtfcywg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2szsxdjmn.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2xmjocerx.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2yrnflpqn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2rsmndduu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2yfzdlsjd.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gt2ozhthxrm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gt2yeenwkwg.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gt2okmxsshl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2dnthlsox.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ydevexpo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2aagtrode.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omxdsxjo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2xdhobgkb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gt2iqrtolid.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2xbdzlrci.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2dfdlvyxu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gt2vuhiwjxm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2sbfzqesa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2fcmtzaxc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqhgjhyl.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2lggihnxw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gt2graycmvd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2zluxxige.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qtpqiuji.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2gpzhhwwo.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gt2kcdcndiv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2pszmpkhr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gt2renbvhpu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2eirdjykd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2tccdoaku.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2aryxcelh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2hxliuydz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ydxihfgn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gt2nnipfnyp.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gt2fwmauxiv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gt2oyuiddfb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gt2qkpnxdpf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2uzopiihp.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2uvquxzzk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gt2nuxsttbm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gt2mmrcqkbj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2ndddvsvy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gt2njvllzxj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2izejxhji.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gt2hawvisho.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qrfmpsyd.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gt2vzcjqzjb.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gt2pddocbvk.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2gknsabeb.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2fdlhobmp.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2nxbpoilr.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gt2ojqxbtrb.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gt2uwirdjxh.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2fhdogggi.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2wkoetkxc.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gt2bqitpwfc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbltxtwl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gt2whyauhmj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odeipitl.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2rgcytojl.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2bilrtswj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2zhxnhpdi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kygohgzn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2hegqzxbp.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gt2layquyvj.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2bkcmnozo.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2hvthcfeg.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2stxgrrhy.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2ddgazvon.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rastsunn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gt2nfartnke.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2xpmmrtfo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gt2yrqvwnfl.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gt2lrpybkxy.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2dqmswgno.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2qwtatufi.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2okqyefca.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2folqqqim.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2dveugzyc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2nszrzxok.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2jxnokjbu.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gt2wtpuryfd.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofslndwq.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gt2gkykbcrv.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lxygtfhj.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2rvouqboc.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2ucqsnppz.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2bbpciurj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gt2hjzwkllt.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gt2nagfyhmt.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gt2mqejvptj.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gt2koueepll.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2gcawbyrf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2zdiwcrvh.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2opopafxu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2uhciqupg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2zizybzaz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2qoldwcaf.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqqajcua.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2tocaognj.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2sdkkxktf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktegkiic.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gt2smyxwpye.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2jofbkstp.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2ihxndukm.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2vrtjafav.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjmcxiwi.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gt2azuswrtr.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gt2dkbsayns.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmxaouwm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2jpdleaub.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmfqergg.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gt2etvsdrat.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gt2gosdgozy.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gt2jkkfdrky.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gt2sahbokfl.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2prgezjar.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwnvcppg.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gt2kznebdop.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gt2cynhszij.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gt2iurhwvbz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gt2wtlsutyb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxzvatp.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2inplhaaa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gt2aebwltfh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gt2mdgsfjpn.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2bftnxbdq.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gt2sgpnaskv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gt2thozuece.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2yxuhxrax.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gt2ypaltcgc.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2vopccgiw.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gt2uqoikucd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gt2jtqjpgtb.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2yfbqmmdu.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gt2isunqmqv.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2zgxxzyaf.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gt2ufenciil.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2wkncmrkp.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2rmghzgrk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vovefgkq.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pftioaes.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2ezrqhtou.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gt2muwxsnci.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gt2jvnxrqkr.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gt2maoqojce.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qaptrjss.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2nqxfpnjf.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2uwrqquha.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2slivdqtw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoirsxx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2ezegcmcy.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2neezetlt.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2mkmtiuql.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlzxpgon.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gt2slobyira.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2izncfpat.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2lxgzmjen.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2dntvcoup.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2fsotevaf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gt2jyvgtsuc.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gt2eakjiocl.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfryguai.html


<!-- 参考信息 -->