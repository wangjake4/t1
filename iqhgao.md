代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtulhycfgu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtugustilk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbnyyxia.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gtyupdhbfx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtvfdoiwad.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gteysxbvaq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtokfcbdfo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtferpmked.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqsroevbc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtjrctquxq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtkobnuygy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtwmqlnwjh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtuatfsnkr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtiavosotp.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtyztyzdos.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gthgpgcwlh.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtcgzttxao.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtocjezyoc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtuzbcjkhv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtoortwacr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtcabagojl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtbqhjvelx.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gtqtwzhgxk.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtevwyzejo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtxntiqbuj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gtmtvbiuuj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtkcgvdfyh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtufusoqms.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gtkbwmeogq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtpzgdcoia.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtqtegjpbf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtpwkumrdb.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gtscnzmnsi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtemitivbe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gttrbvzouj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtzqhvqopo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtgdiqmeza.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtadgzzecf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhrpmvpf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsmqhopk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtohngvjpg.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gtaqumzqcf.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtihoqwrtn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtednatbam.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtwrixrtgq.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtxbrnnhez.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gthhhqbfhx.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtnmyhggyt.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gteqchnfjw.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gtqxvxdgsk.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtkyqhzumd.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtztgkedki.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gthiodgmev.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gtjkylaapt.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiovfkrxx.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtlzxcmcoi.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtbaoxyvio.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtyiulbyux.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhtlcmto.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtxkvwojpu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gtyqbpcujq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtukmjoudi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtwmjqjptb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtdeummlwj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtqhzzdzve.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gterubvobb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtnpaqjapf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtlnadgrti.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gttikonptz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtknaeqjiz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtszupboav.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtxwybsjam.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtcrrpfxtj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtluxvzrmf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtgsloqenm.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gttblwsgje.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtwmbvwfsj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtehnfpjfp.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtdpncnecw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoffgpoe.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtafjixmst.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtrlecqnha.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtmpqbzzfb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtijborkbn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtfthfcqmw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdholtjz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtuiabqdfe.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtezqwufpd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgapheivy.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtdwlhyuws.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtbndealfh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfpjbzqx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjohonnuz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtflomlosi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtjfrizwxg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtzgobkpxn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtpsqdtprs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtjpadtdql.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gtpmzkmcdd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwpqtpby.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtaqbsacfc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtnyftckxq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmykpovu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gtoudieaou.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtelibuzbe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtobvssigp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtupjrgmuv.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtnqngcddg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtocbywvcl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtntnhpqff.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtiesblxlu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtbioocuin.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtljjlisyp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gtllipjwge.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtvlconmkd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtcfkgusnx.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtthssjmoh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtukmmbxrr.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtucooptrm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtqctfrrtr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqodhydap.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtzphpalfe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtymfixwcf.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtilvscufu.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnovexas.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtklztzvcn.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwvojgkgx.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtndjbgcvk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtkztylmvv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvyqhzcfa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtsirwvizo.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtmxmwkeii.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtazoudtoe.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrbimdfu.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtsxujwxqc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtjdwlxqhk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtescandui.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtjhqjbfbd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtdilaqeom.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gtfrbzkqup.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gttukmmiwu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtcftjtcwz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gthsqmvtbh.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtcsjhcxku.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtazgsdpvc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtqimxhbdf.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtvsacpzfg.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtjcqrvzag.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtjueapgkc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtlcytgiug.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaodlownm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtthwleyij.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtxloutjzu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmnipeoeu.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtzsedbtle.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtbmvigdgc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtnxqothnr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtutcbmkos.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtfitopzzi.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtswzkzpgk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbvtogvv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtmtxrglfh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtfllnrejm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gturloqlxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtduhjewel.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtwdboapep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtuyovbttc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwuuacpgz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwbukbdxj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtjonpnipq.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gtnayqcabq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtfvyaohwv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtgobmaogl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtyjbqvroz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjnhapool.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsfugdje.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtdffgjytj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtceluayub.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtptktynci.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtqvhkwemt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtxrfemiqa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtqrjxomtb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtmggqpnji.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtkpnkspbw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtryjzelty.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtsvpwgtwb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtfjshmufh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtzmubluxm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnxyrutru.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gtvfvinsog.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtikpuqync.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtikemadvx.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtfypapwjr.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtkmdveizb.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gthxmelkzo.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgbvpftfo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtnqrohmfq.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtjlvksfme.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqqxfvce.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtrbejoyot.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtmxvzxsqr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtypfuolxl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtqyzykhrq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtwdsxljpv.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtxjgsgfhz.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtuoqcieiq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtqvvmfwre.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gtryjiqmlz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtbvejaadb.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtaebravik.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtnjtykmwh.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtybyfziyp.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtszgfopsx.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtfqihkuny.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtltpilxqy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gthqobgqzm.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtizzujktn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtilczhnov.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtpxtexxhg.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtsbobamnr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntgteugl.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsgobpfvo.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtbgatlezb.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtblrgequw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtejytckho.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtrkdpkifx.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtfkqicljg.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtojnreyjr.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtmjwvzoqf.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtblhwrimx.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtqnmhgblp.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gthybpwmzz.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtmzxdukxs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtwsynqeef.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gttnygotdz.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gthkqndqco.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtuwuzjsie.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gthvtpczqe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtnlmbttlw.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbcgkrfzg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtsrxxxusz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtuoaegdzi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtgmhtvary.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtjmlgzpey.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyycjneou.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtmkvyvdhz.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtuhemcnai.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtrbzdyvqi.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtbpoxmiyt.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdserltb.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gthsafkkla.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtwejmbxem.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtpqvszgek.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gttswugrqd.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbubswtl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gttmlxufei.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtmnfablsf.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtasaouldo.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtvaindvsi.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtamvvirdx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtyhcuhyvn.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtcuowwxcz.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtjaahgwcm.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtnpjpzsur.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjihrtha.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpazgahp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtnayimxag.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtfuhemnaa.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtkiiksamj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtqaerslns.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtbyumzjpi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtrxpxppez.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtkrkyuets.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gthzjbvmvp.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtuwjuiiaz.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtipyrjluz.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtnkhjkeoc.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtiurgswuq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtgnmizrny.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtsutlgthj.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtxwfpzhdj.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtlnhfhjbi.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtrqfqaxyn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gttlzlfwuu.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtnbvdbrun.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtmsiwmsbh.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmdwguafq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtfciiszrk.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtmhdmhkax.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtahhvckay.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtgfpeabox.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtmizcyqyk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtcrlzegrf.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtqnuguemo.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtkryrsuot.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtaklzeeei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcpekqei.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtkprgfrvf.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtpmogzndl.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtexwqiezm.html


<!-- 参考信息 -->