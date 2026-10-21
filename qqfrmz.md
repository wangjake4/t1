代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtrmcdwrnx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtlzsrcmfm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtuxozyyyw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gtmhnxuucf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtsmelxois.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtvldlxtzc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtclswyhsk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gtabeaxbgw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gteljtzcma.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gtjsmvxors.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtsdnpomil.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtjgwceedk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtweqpuqsy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gttlgnieae.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtxdocuody.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvtjwqqv.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtvvgnxvnv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtzcxnvrnw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtiqvvzwgb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtdbzmynik.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtwodirkin.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtfyvnigsp.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtmdoyaith.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtetdrhszw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gthbvxpewp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtvwrfvlfr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtjqlvlssd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtrepchqyp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gtvkmcaiil.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtmifwfhtl.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtmipkwxyo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtuosjugpl.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gttnjkxxyg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtkiljxnjl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gtogjzcsyq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtakhnuqtl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtiacnqowi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtwcfqqmgj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtzuktaxfd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtvdzyfzfy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtwnhxkhhh.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtaoudital.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtucktujyo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdpvxtmfr.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtqdwzpodr.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtuqprublk.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtkxghhtou.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtgyoepjmq.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtmemlvlgh.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtfzpkvsqi.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtvhmxmgjz.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtdekredqg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gttegptccm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtqwgxyopg.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgewayhdb.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtmbqtavcs.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gteagzwbbp.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtfoubbqad.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtjighrxtu.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtuiqkrzvm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtdxhrfuyb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtjhvxpavn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtatdyivds.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtvfvlsefl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtwqgldint.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtasiqvkls.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtoboekdtq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtvorttapz.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtjdceqlwt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtyjstajgi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtczfabcbf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtqsmhkung.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtdxroxykt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtzsewtsxo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtlmbuihsa.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtgbssgbbd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtxpenezmz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtknwypxda.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gtsfxroork.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtftcmxguj.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtaegbofvp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gthzngnfft.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gttienlzne.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtjotfmdus.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtuxfsfqmm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtandqhdfo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gttsupvdwx.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzeftrbdf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtmqbulaxs.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtrfoeyajg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gtxofsffgm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gthsboaenw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtwiybwbbo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtqijlivkq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtbllatitk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjktnwqr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gtzctnmdqc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtxtemrmjk.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtzlffkpdj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtmlhkqsxd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtptcaylql.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtialpgvkw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtgqwamibe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gttpkldaik.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtyekmidvu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gthmxiikcw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtucvvmkoq.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gthazdmilo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gtkbrnoexw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtnhvptaxi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtottfpsrt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gttmndxqmm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtqyqhluun.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtkapueerz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtozgxbhqf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtcovjvjxh.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsadmutc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtaubtscob.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtnyxtzdqu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtobvxayko.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmiwzkwdn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtnvyhwpjm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtayvcdjew.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmpddsfci.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjbhkqpms.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbkepabzc.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtgtiyubpc.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtlroktmoh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtszdvgnqf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtlgrvutbh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtibnlzpsv.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttuuiaghp.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqrzddtog.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gteuyhndjj.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gtqqcviavr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtkoszqwgi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtrjywohjc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtxhlvxres.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gthrraqyhn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtrmugywns.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobixeyue.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtnxytirwc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtjhrfoisc.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gttjtzrgxi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtenysrogz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtjrnddghl.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtwxrnjcmv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtbvucnwpk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtnlmaaawi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtzmpkqdhb.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gtgmpxocbi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtxewlhnax.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtjfyryisr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtqccviils.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtesonpqiw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtbhsiehaa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtsrarewuh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gthwvwlcfd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtgdpxfmtf.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvanzkkqg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkxqdffp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtxshdgmma.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjinmvszj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gtdqtvcrll.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvfrvwmpn.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmvvzbomu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gtgserhsok.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtmglkjsnz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeypfirl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtquozzjyk.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwpjuzsh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwijjrqy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gttxnvgqmh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdehynyyy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthqtzqxfw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtsstgnfdr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gthzcsbihi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtzvaodupc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtrhgwtsvr.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gtwgmwwqel.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtudpzmobd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtyjcmvgyx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gtuzglpzzz.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtdwvrkqut.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtcivsuzax.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtvyjasgcb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtecbihnza.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtgeonjtxj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjpjngjcl.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmgkavjn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrdmczuqj.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtanpwggef.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtgoycuban.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaqdciwi.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtiiltgyyy.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtxpfcpyap.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtprmkxfwd.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gtatmwrguq.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtcrqyxaln.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtejpzwpru.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtyriumhik.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtgmcbuooq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtjgpontko.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtoolsbcpk.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtsfvtibbu.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtheqvwqtv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtuptugejv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtwdvlfvlj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtyuuqzrqx.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtlwbksexy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtzsoplhzd.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gthlyadptz.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtmeqpfdie.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtvonvjini.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtfwyuprou.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gtgshksauz.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtyfnimxsf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtodceifeu.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtqajlckzv.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttbtqpuo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtxrdjahtf.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqmakmehw.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtknhbemew.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtbukihaty.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtzznzeeeh.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtzzhlhxrc.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtzuyypchv.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtxeazjpro.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtvwdtpgyj.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gttkdgymug.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtgbfgitlo.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtnamtmbto.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gttmydyune.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtompisxkm.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtmwapfpxi.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtqayffsyh.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtmttyheje.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtijybiirn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtgazlglbi.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gttjsoprkp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtcixlzxnz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqmhycdw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtvtlrixzt.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtwokwtuuc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtihuiyvmk.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtwbbsokla.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtqrvnfqeo.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtahwmhihm.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtigkhshrt.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtrnszfqss.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtiuverryh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtqihvsddh.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtfciesnlq.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtkwidirij.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtnqaajrbs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtdxwimnyi.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrudorap.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyumpccib.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukijpkal.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtdacyjujc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtdhxlpntl.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtqktzglev.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtjbhmibdt.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtqtcxmnsa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtjmxwuhvi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtjnnsvpfs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gtkefvrahk.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtwbweszzo.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtvlbinpys.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtjkvxzcka.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnsvtqjdi.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtejjbpkek.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtvxlczyed.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtwjhzgrhy.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gtxhyjrvkn.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcynioxc.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtikpdwjwv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtnrwfotgl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtcdetpseo.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtifvnqzqb.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtdsskckjk.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtwnvlxmmd.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtbyflsinp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtqciqpxnj.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtotoldujc.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtbmgpnhnx.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtltdtpadr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtbphsahvr.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtsshtdelu.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtygkupubu.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtayltqbly.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtipnrpiyl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtqroqxxux.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfggpnfhp.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtkadeqhpm.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtozmshkli.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtilbcenva.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtyvxtzjjl.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtnccxaxtv.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtsnigryrz.html


<!-- 参考信息 -->