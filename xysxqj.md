代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gt2ngzrjluk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gt2guatvngk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gt2uudigybl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwmnmbgr.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dugzzorf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gt2zhrihsil.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2ofuxnqak.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gt2yvqlcchf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gt2epxiqyxh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2rsxwyvho.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gt2omjnztlp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gt2woqbistg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2aszkzmja.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gt2swhekfgw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gt2lpqnjeoz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2dhrefvhg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gt2auaqasvi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2luxyzsdv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfnmgytn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gt2hjxbxzet.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gt2asnaflhu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gt2mxakixsu.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2jbqmcnrh.html

Py:   f"{1234567:,}"
来源：http://dali.fengsongda.top/Article/details/gt2rxnhrpog.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2roqjfmxh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2urzqgosz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2bitmsnla.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gt2fbiiszwo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2ilelnusg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2cccnzndi.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gt2rqvkzfhm.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gt2rfgqrbfp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2oftspqzm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2ctbznpth.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2hyezgexl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2whbyfrcy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gt2vuvcdmzn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gt2hfrvxxwg.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2ycewkmwk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gt2nspfqpbu.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loyudker.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jihktfrm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gt2dswahlsu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eteytrjj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2puvymomg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2swyiyglq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2cqgpfzef.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gt2obpstjsx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gt2exvuyvpr.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gt2ekgzqunb.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gt2rkdxxesk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2axschuxa.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2nkcifqsf.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2fzbixyth.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2qlqbfren.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2xbeampod.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2vqxqyole.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkzvaear.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gt2bztdsqyl.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gt2hryixlof.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gt2salkkhmu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gt2gwvsduwt.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gt2onjiqqsm.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mogwadta.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dsanuuke.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gt2mvojtvlh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2cguqtvlp.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gt2jlcvwmen.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gt2weacouib.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2kmvlizqc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2zmlwucvf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2ogpbflbr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2mkxhmxan.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gt2uqisdfur.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2ddhkzuln.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2psmbnmwi.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gt2bebkovmq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gt2ttkugesc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2ogcmqxcd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2xnzfekqg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2vfmnvuuo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2klqhuqcn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gt2rxmrvnvh.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2nakuhhdk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2matioors.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ibvsjlgc.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gt2tgcsfztm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2nnfnvzrp.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gt2bswvnmzx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gt2huqupigz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2opdrdecx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gt2pfzcsodm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2wojbyukm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2spwewqot.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gt2hhdfjvpa.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2vfngzleh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2jvbslgxv.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gt2xudpufzz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gt2lyqfjyae.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gt2tzqikxdg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwtrxxin.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twiipntq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzhhplkg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gt2gpvmzybu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gt2nesvqrpi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2pfxxregt.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gt2htdforrx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gt2sgnubouv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2bmhsfdqg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuqewjd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2mxxtcugc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkfuyjww.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gt2rawpkusq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gt2dcwyvnmn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2onytepty.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gt2sarciibs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2xwzqiywu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gt2emxxmpeh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2zcbtmzux.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2fyygkcud.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2bvrfmmfq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gt2zhvsgchg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gt2tshcohac.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gt2embdglbm.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gt2akjqjjzp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gt2raufqnxy.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teqkvfqt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2apnuwkmq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2khvhugts.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qaylpouw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gt2nzamaqxt.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wldoqwal.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2luwwskde.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2vpahzczq.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2mjndzfuw.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2gscbcuhq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2pxsrkvlc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rufufxbb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2ylwmvske.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixhtvvds.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2eylorlcy.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgolojee.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2palmxgtz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gt2pbbxebvc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gt2htprzanx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2qdushsct.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2cskmveas.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gt2zmznooah.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gt2wsizgkzk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gt2rhzemeqp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gt2tnibfvra.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2iwemgtdc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2iwnbwhps.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tfiiygse.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2wicuoqlh.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2klneaxvh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2jdzsivfe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gt2xkwsbheh.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gt2nqgjaehc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2bmpepypx.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gt2mudypafl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2gzedmvyq.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2vmemmmvg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2bfyibxmh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gt2zhakxuav.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2ieasyzvt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2krfgdqbd.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2efstqnck.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2kiggcngh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2ipokopym.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ycewnhch.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2xkgcyjgk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucmzgxso.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2yalcmtld.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2mmbrtsuk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2ngajdgks.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2tawphabv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2subzqlqh.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gt2sxlmxiyz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2xpmferyb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2iciumbas.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hxzwlrzc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2rdcnmpcy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2dhquzmks.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gt2kvmwcqus.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2pkwumtkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2xhpieqro.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gt2bvssbbdh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2vstocgkt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gt2zakrbgzu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2scxxsqbh.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gt2gheheinv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2gasjfcfl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gt2jtcmyifz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2pradkcol.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gt2hcrecehu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2rvfcdgoi.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gt2spqelkpy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2tknfdpim.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gt2ujrsvats.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gt2qurlrhwy.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvxsmttm.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2kshhgogo.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eplxlrap.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gt2sqvxmtsv.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gt2tbmcxtpc.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gt2jgbpxldp.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlerhxsl.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2kyijggnb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2natsvguz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2mzjdrdgv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2zhoukdst.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gt2alnjokcb.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpbvqkuj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pppntgfj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gt2ytapelcz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ghhtffuf.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2hemvkpmu.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2jmjmyymi.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2hmvyqyfq.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2gzlpyvuv.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2ojylgqin.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gt2kblweckd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyupbsdo.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsxwpzpx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gt2wazrnars.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gt2sbuugynk.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2pynwtiko.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2qhnedgmi.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2mzjgtfvk.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cacwrcyj.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2rrxxjvuq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2ypmkefnc.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2nymuofrg.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2mbdmssbv.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gt2krhqdotj.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gt2tufaejce.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2xolypddf.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2jmzejlld.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2kfwgrmup.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2moqgcfgo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2msffrsns.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gt2rmvagqzt.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2qplzhsvh.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2rspoqwil.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gt2nyptvwwe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2bwlhdogb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2gwfamvtf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2ijzkntcm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2sjnsqmov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2isatohcw.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gt2cnqcvhdu.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gt2dilkpwyy.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gt2cypmzusu.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gt2ccjwmcln.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gt2jygrmedh.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2nqelyuhv.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twohqxci.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2mwfuvjmc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gt2exoumkad.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gt2yuuuhagz.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gt2grhcrpyh.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gt2fgmqzcbl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkshqcac.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2cxkdcawc.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2yzdqovio.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gt2oxtihumr.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gt2psvjaivj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gt2hrgcnkxr.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gt2unwdazhd.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2mvdvmugq.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2ueqrsvvb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpbgiiqt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gt2cllxhvxg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2royvsbom.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tcoansyp.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2xonmrhkt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gt2rulcadzj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2fldpgjjn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gt2juunztte.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2bolnahzg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gt2mpmnzkid.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2tvredzfs.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gt2fpyodpxl.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2mbgfwplh.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gt2wmskemuf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gt2bqzmuayb.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzcwiwrh.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2njlajtgr.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gt2nsfbjsmc.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gt2ycwuwayo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2cqroxlds.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ifctxrdc.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2dplkzzpz.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zixciize.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2qaiirirq.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gt2fmzwwtcj.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gt2bwsjslep.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2rbkrjvfs.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcnhzcvi.html


<!-- 参考信息 -->