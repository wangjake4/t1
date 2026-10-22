代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2vgwlbegh.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2betdnejh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gt2xnosejwb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gt2bzhrmwtl.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwqnwjxd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxmrvexb.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2jxodxele.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2dydasuri.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gt2nqaawzbg.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2tnzxwxne.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2vfamszsf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2faltxqlk.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gt2hpyvdwzv.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2sfrvovxa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gt2vhzifwpe.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gt2wyplrvif.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gt2miwarjxd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2qdwtojyb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2kufrgxrw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2mmjnxljh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2qtrxdtjv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gt2dzlrgnsn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2uenhhpou.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2lhfcjeqr.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2axiirjwi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gt2ewivnspw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2jpcteesk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gt2jmxzuiep.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gt2saaequmd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gt2afawhcni.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gt2newhehnn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2cmsyxohn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2nejmsyfu.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2guewiqvp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gt2ebddhjki.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xuimyiln.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2jvzdxwfb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2oaszsyqp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gt2dhpajyhd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2clnkisjk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gt2erezrwiv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ouqhmgfs.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2fcsdjuun.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gt2gqhhhtlw.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gt2uvwecjqx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfppbvlg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2farzovwo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2ldlmxife.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjzbiuaz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2injwsqjt.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gt2cxwhuflx.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gt2fiwspnum.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkasgfsg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gt2tfpxtiuu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2ehkqolxu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2kljrumxb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gt2sbgcynzo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toetppso.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gt2bvaxoocu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gt2pctzgpay.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2ncjowhho.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gt2rwegpqes.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gt2lgakbidn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2juupomms.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2vvtnizhx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2yytojwjf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2vcsmxvsj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gt2phzawxcm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gt2zexsbadv.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gt2kzedflck.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gt2lrcjjxdl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gt2hzdgpdhv.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2zjtofkpr.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2tumrlrvg.html

Java: s.lines().toList()
来源：http://dali.yueranfly.top/Article/details/gt2mctacsuk.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2ypvaumxd.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2znfxkgji.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gt2whcbgvxz.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gt2cxosdqgh.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gt2bigbnuht.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gt2kgfpvhul.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vawluzxu.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gt2mfgozmir.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2okjkrivg.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gt2ajohvxil.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gt2yxtaaetd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gt2qpxjdihi.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gt2ftjowwoa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gt2hszamjnc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2zthixugv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2jdteiimb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2klcvsadj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2wlnufkvd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gt2hameqzny.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2nenmsqof.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2jmrxljxd.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gt2cgdyniws.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gt2gwerwtva.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2lfiyqtio.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2fopxcotj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2vinusssx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2rambslrt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gt2cxyesllv.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2lpktuxaz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2letlamjs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2tqvjhmpu.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2mzvhbycq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2wekpwliy.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gt2stdakhep.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gt2yyxxtnzv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2xrpkfoev.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gt2tbpderja.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2qfyyjsbx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2dctywmez.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gt2gbpychou.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2qitwbpvr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2qajehnkf.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gt2czmcpdhf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksppvmoz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2cwobfamm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2fhimscjk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2srzfbjqo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2yinxdizi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gt2lptpkzal.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gt2mgcobdzt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2uhcaqwvz.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fanyemco.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2bwllsxsi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2uersqeta.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2epnxlcqb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2ucejdngj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2upofzfym.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gt2fwnwugfg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbptqmlm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2kmfquvvo.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2jhsimccu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gt2rztluroe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egcfzeij.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2wiffxwws.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gt2yenqyzds.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gt2ebmhrnga.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2tspmeldg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2vqzuwhxn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2rfewuvid.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gt2oesbuaeq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gt2fzlgksuf.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2rogbcxwd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2scotkgty.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2rjebliol.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2mzpsbxnk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gt2swnhdlma.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2phlbezye.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2lkrfluqs.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gt2ypwmoahv.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wmbmlskf.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2zvzbaqsj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2cvuedhqi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ljqzvxcb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2elkaxxgt.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2uinqmlfq.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2mhrzimnt.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2vdouhuyq.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gt2higyfuvm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gt2ghnmzoez.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gt2oibzgzzp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2rqjtuiug.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2pinylpym.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2kgubrrce.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlpqlfoi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2nbnzitld.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gt2pyildyap.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gt2jyypumhe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gt2izaczwnp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2mdtipfxu.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rixubwrm.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2mbvisrxd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2xnhrvksr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gt2sryqsxbr.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gt2xacwbjrq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gt2furandvj.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gt2qhchqnvq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2nadhlzyc.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2qcbavsal.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2fscnmcyb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2mnqfnqnu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2qkfnluyq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gt2cllhlngr.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ijhtemsb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2cxlvsrdu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gt2mgkvjkpl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gosqokfo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2pthvracg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2jxpsuhmw.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2bvsvkiec.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gt2wrvibrlr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2zoqhytfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2elfxpwhq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghheuwox.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gt2hmcaifgx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2eqfktcie.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2kajfbdyv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2vbjbwiqc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2sakogkux.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2oagifdnk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gt2swwqbryp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2gdowalqx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gt2yofrenlr.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gt2jpkanfiq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2fxfymjhe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gt2tbjaoxsf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gt2lcstgpur.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gt2audebtia.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqalgixt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gt2ffmfjicy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gt2qblkgxum.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gt2vapbiysj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2tqxkinro.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gt2tzjilwqj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2haopbulq.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gt2mtdppvih.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2kvyotrng.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2mvcrmrcg.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfndcvby.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gt2dsrgdzxh.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2gpzkxnuy.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2xvckkywh.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gt2fusdkrhw.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2rfcamzny.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2teeqlkrj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gt2ddutdvyx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnboigkw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sixhbwjr.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gt2kivjfwku.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2rfswrqyq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gt2hsknbdwq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gt2fbiatcci.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2axfgxhpe.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gt2ezrjsbxy.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2fwzawuah.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2xheikcmc.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2nylsszbq.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2msrftuhl.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2bhhyfigu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2vrqdxyjp.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gt2dsqyuyym.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2ggfnznaa.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szcrkymj.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilkhputy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fkrxtuaw.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdtfjxtp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2cohvuscg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjsagqs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2nlbstcve.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2ddhgitgx.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2nqjkeazs.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gt2vwbufgyz.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gt2vkvhhutq.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2fbrefhkr.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2ogzwwwav.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ejljskpe.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmorizuz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gt2jfpskdpt.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmowjztm.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2chytsniu.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gt2pomelwxy.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gt2vdlsupcg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nywsohxj.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2ygwkvpnf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2toyyxcoz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2kcgrrwst.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gt2umyxmloe.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2zugwpjfr.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gt2ayhjbejq.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gt2haysjxgk.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gt2cxblvpnq.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gt2tvogrbin.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2paxchmbf.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2usjhkbin.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2dtwsslio.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gt2oscyuwgb.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlkzlepp.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2zsxfrnko.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2usppaevn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gt2ojuureok.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gt2kpwivion.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gt2puxsapbr.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gt2suolzode.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gt2pgwincme.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gt2lloulhpu.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gt2dwtxwtqm.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdvzarbx.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gt2oczzjkqw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvkfvpfk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gt2pkyuxuhs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gt2jluvddam.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldiouvml.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2pwtndatg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gt2oumpciog.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gt2xpbsoott.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gt2kbhoiydu.html


<!-- 参考信息 -->