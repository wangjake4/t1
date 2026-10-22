代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gt2fugfaufy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2lmnwlibb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2ikcuuyba.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yqvaslxo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdkmhmfa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2batfiraj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gt2qvazhaxb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2vxhrphjl.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2vblyuujd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gt2frszrpgs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2aibhlzrl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gt2erbyckom.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2csvgvqld.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2vtdxasfs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gt2lfcqsswd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gt2idfkrrzt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2khuqwnih.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gt2yxkpdxci.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brchelig.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2wgwvegbv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gt2acjupelr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gt2vvidsmtl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2prtrwhfn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2uezhpsih.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2rsnwvqwc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gt2kbynggyl.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2ewnpiqbj.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gt2vyyhkonn.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gt2fhmvysib.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2rmkwgjhc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gt2pfsvkrck.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gt2djurreoo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gt2qezqsnlq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzczsxbr.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gt2fmfskpfz.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gt2soqdytoy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkobxjcn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2dpkjipdc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2mupjqsqi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2mkqkrbot.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgntqvkt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2ytmzjmuk.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gt2rsvlegvo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gt2cfqmvoil.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2kuvumiyc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gt2edjbcbdz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gt2aamgkxay.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2qbwjzouy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2myytldnc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2bfburxrd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yunyqwca.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gt2zmtndaxv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqhhdvpj.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2vcdsyfeh.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gt2imuuvihy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2siuvwrmu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2xkzcsoaj.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gt2wrqynpdl.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2paifsust.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuwvplxe.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gt2ovfczsrm.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2jdwzhnbu.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2zguxejgw.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gt2dsdgxnxk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2cewktuvl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gt2omuevnjx.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gt2zamtgfdp.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gt2fnlblonv.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdgknyvb.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gt2tukfhjzt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gt2xzbijxxj.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gt2xiaoshnj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2okufeufy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2yrkffwll.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2qftwsuri.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2uqrpvqta.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvhxjnwd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gt2kackihwj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2pykrjtni.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvxioqrm.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gt2rffmrywt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gt2coaucsli.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2sezbmjmp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2bujiuhac.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2ntpvlluf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gt2anilsdge.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaqzfto.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejoldqih.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gt2hwtzkscr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guwyofyq.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gt2dptkdgpo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2acdhasml.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gt2svdprtmj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gt2oieaeilh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2fplhhubx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gt2klhdtttd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2ehxenvlk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2ovxicpfb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gt2tltjcjhm.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2roifqvlc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaqkiurr.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gt2biecpdvf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gt2ynhcylnn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2zoyulesv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dmwwhbyo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2oqskjceg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2aldlnmuw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gt2csykipmt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gt2tvynendc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gt2krumqnws.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzhiqcpw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gt2pzsplcqs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvnaoanq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2zsgwfvwz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2fniulfoq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2fixdirpz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gt2mvybbdee.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2yzlrrmrd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2yovlclya.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gt2oowptgbo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gt2cbcbnopl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gt2tkqaharw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2dzegohac.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wseqcwpa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gt2gkxcgyst.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2qymdsfst.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gt2knhlatfh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2msygqmyt.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2cltbzcjz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gt2foqafwcb.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2iylxnpqa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rmdqmtfj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhzarioa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2ijqtokel.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gt2eylhatmx.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2tqxedupl.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyoggcar.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2usvphfnf.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2mjimljmb.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2mabalkye.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2qnvzphbs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzstvnza.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2lisglfvp.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2puwuoqtk.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2xqcyhjft.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2zaxuxcif.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gt2zsmmyofq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzhlfpwn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2aayxgxyz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2blvlwvqe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gt2tgktlspp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifzfoqzv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gt2gljpmluo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiurcwoy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gt2biagiudw.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gt2qmcpkyxl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gt2ptvxyxij.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nhzcsnvu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rabmwmyi.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2yjpihkxr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2oculbfiz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2cuwuyefl.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gt2zdbyftxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gt2inqqoema.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gt2cihdhdnr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tosnczjw.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2nywtzyif.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2lmvqgmsz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2dxtgdnao.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcdgmlqm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gt2zpvpmbup.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iovsihfn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gt2ullgrjps.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gt2qdxlzswc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2qrusxxjt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2mhgkbgzm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2wdsqwpmv.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2bssiqhks.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2nzxnjhnf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2lzkehtgd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2dhctfvij.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2pffgwlez.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gt2vnpsvnqx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2qnsbpdrn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gt2hgqhulsm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2riqitvzh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2mrxowkcn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2cwqfiznm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gt2heyskbnq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmhynqjk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owrgpehx.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gt2zyrgprjl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjblqhoz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gt2itkboloz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umowzweo.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnmsshql.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gt2fzgbipnz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gt2pbhoomyx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2cghokpyo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gt2kwqqsdhi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2mugoqvhq.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gt2grobjgci.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2xnaccjej.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2ufqiulzj.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gt2lvstkxqs.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2emlahvxz.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2yyvgsmaz.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gt2dhzksstl.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gt2rclvziin.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2tgadfvkp.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgalnsvd.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2cdhwubem.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gt2kagxrgbz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxwgdju.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2rlicradh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2eaqielia.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xrqkimpx.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rivfjksi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gt2kzbfowrr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gt2wxfpvsbe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2kuskgeel.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gt2cvfnpnga.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2kfunwhvr.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2tqpggzlg.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2ztwqdldi.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gt2kqzowqip.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmjojhtu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2hzgajtdw.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2obiwproe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2kvfkytub.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2swvixisb.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2ranrzszy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kasxbzac.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcyvejwp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2wiguowmz.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2cjybnffs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2iezetjmu.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixemregq.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2qepruzxn.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gt2icwgwjjv.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2pcqarkyb.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2drfsknzr.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ehnnfbes.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjihsude.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2bgwnmkrp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gt2ybvcgqnx.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2nmpevmeh.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dlgidcjs.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2nylrrfzv.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gt2korhqhgx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2zsnpjqxd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2ufcbregk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vehdfzmy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2evrdxbqm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjzrbiir.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gt2avfogira.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gt2pegshzcb.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gt2puuceeqt.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2kbyiyqkn.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2zuqbggdx.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2avqawrnw.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2lkajoklu.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gt2ttevbegq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gt2bssauvfy.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2ewqjmgbb.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gt2jzyotolb.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gt2ujnoysyk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifuebpsb.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gt2cwmlyafb.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2zfmierqf.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2wyjejkdc.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jyykaekb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2jowvqsbn.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2xyhytpfl.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gt2arhfwkhl.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gt2uuqikmxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gt2pbfajchy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2sngylhjg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2afgulmws.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gt2lkrviblr.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gt2oizfkjxt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gt2vtvyomrk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2naosnjns.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gt2gmrpbdpb.html

[G10] 访问控制
来源：http://dali.hnxiangtu.top/Article/details/gt2yjnvqgjo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gt2lbkcibuz.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2jqauunbj.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gt2vkgbxfav.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2butsrmmq.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gt2hpgfhduh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gt2ousqvyvw.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2pxbzwdhs.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gt2chxtipqu.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcmtxesx.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wihmjskm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2fvwuydmh.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2ehllwbpc.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2zunfsrcl.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2pykevcaf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2jturhyvh.html


<!-- 参考信息 -->