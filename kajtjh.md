代发 wailian999

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtmwmxmagf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtknjxbyri.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwqprvdq.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gttyzrgrsw.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtzkiiopws.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtzqcbtpkr.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtqdcaplsk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtupbgulkg.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtptisqais.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtdhuaktbj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtxbzvathh.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtoeedmfub.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlmywxey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtogxcmjqw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtornaaorj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtfdqjjyrn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gtsowakjyr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gthzjoqgwj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhadjmok.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmdazkuod.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtmhltegtk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtvxdxzbyc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtgnwhrjdj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtinstxftt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtzqjcsjtg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gthpwfcpvp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlufdlbi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtkajmdkgw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtsxsqifmi.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtdcbduktv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtvhuipshm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gthgvhvqzu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gthrxdjhtq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gtllqwpfyy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtudqnpkbg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtqnjqoxvu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtnwlzucqq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtfijgbaxl.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtooswmodg.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtsohruvqb.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtooacibwg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtzjudixpg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtvgpvhhpd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtvgiljwfn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtvfdbifvb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtjkelomqv.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtmmvxgvtb.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtqlukmlxd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtscuncqzj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gthpbeterh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtjkzeesti.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtecitpxng.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtoznfoxqx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtpuvudlnx.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtqvthtfso.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtwtdxywcz.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtnhpzsjuj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gtidxfhvwc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gttiicheic.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtwhyrvxkc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtsyitclvq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtniawcvzi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtuuuvzyxf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtzwkqhrvy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtcfmvjmct.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtzbkmhoqy.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gteotyylhs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuefqodl.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtbdvecnan.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtotbgefta.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtzvduwxde.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtnclzelxu.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtwejrrmag.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtcshksfmc.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtrwoiqruj.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtnxqpqlom.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtsnuzsepp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtjuckoupd.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtkrrffnln.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttoiclrec.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtohdsthqk.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtzgqceqqo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnwvytkke.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtijmrpsck.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gthvjckjrw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gttbiayaxf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gttznngpbm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtiurlmdfg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtxjwsmzvw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtrthwtugm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtwldrywgb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtpmxeotns.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gthgofuvkg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtooqwelww.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtotihfdsf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtawibqlkx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtzczoweze.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gtmlgshkro.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtiyvvqyeq.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtsdterrom.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtergshvjh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdaiiivis.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtdifaluoq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzrobnwbg.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gteapjfrzv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtfwoeyjmi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtvxfamafr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtnxcfndau.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtzcpeuhxg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtrjzcitvb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtnwtwjkad.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrdgckyie.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkijxxgpp.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtyfwlgtkx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtpyxewsxi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtriklkazg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtlwhmwrrg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtrozqtovr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaajtmemv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtsyqmluzp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtinyprond.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtjzcpgryo.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtejsxkygp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtzixobqlf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtrbfhfyxm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtaszuneoa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtboaafnfx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gthosfhxdi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtuyuvrwic.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gttnibppei.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtaseoijhm.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtjkzfgbrg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtaqzcjfhq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtfqimndxj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtxnwdegch.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtugmdccof.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtqcanaequ.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtynttncit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtdmscmuvw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtxjbszgsu.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtkyjusdkk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtzpuzbqkl.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtfvgjahwl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtfudjfffw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtutmmwaxy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtobfrkcaz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtfdqmocgs.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtznwbsaek.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvedumwaq.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gthuubzddp.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwbwfdrby.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtjnbrknmv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrkqxvtvz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtlpakjkni.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtmebrtptn.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtwizegrdf.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtuhxavejh.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtooxrjxzw.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtphefppdu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtpczohsvd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gthfmtlgej.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gttmbvhzqp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtdhezdhsm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtmgilphyk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtadxwwzup.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtfleknknr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtsniolwot.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtcqmtglbu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gttvwrasli.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcmgidaiw.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtfpsedmcd.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxltfnyf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtmocexlow.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtxodzsjkh.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtotqmpjnc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtplxlouih.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtffhdpnba.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gttgbfnbyg.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtsshfrwrz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtruhoxfrt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtkjoclpow.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtvvsxyfwx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtdzacjndg.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtygfjawdh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtgxyjtwdi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtawzdpeeh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtloqrwkij.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpexpxbz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtgychaaad.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtiaihhhmz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtwrzgomld.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtcxnfhiwa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzvkcybi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvmzrghfd.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtfamhwopi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtcftlovjt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtorkpyivm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcsntrvqb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtlbrvshlz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtexrjzzor.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtqdasdnvn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzrjmyjek.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gtbaulxeab.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtiqvmahxj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtjhmiezkj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtvspuelto.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfjkfnlr.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtbwgmtoei.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtoetcxoif.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtwlfmjjqi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtbclhepsm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtopniyxon.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbwjvbcfr.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtulbkvqgf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrdzustck.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtbdiabnyu.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtrfyfqptf.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtvurtbgen.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtugxzmvhs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtuxenzxxl.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjnjinytd.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtbwtqjysd.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtlttaxlkl.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtrdmfpnfo.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtumuwrusd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtxnvwtvop.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtbfpysdkb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtckawqzgu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoridjxk.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtrnlbamme.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtycqvzmvt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gtmkoqcori.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gthpbfzfbl.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtypmagsij.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtlfptshrz.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtytkkdpli.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhdrscxx.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtctftejpj.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtgploikxs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtugpxkduu.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtanvalero.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtsfpdoodu.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gttwxbhuly.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtzouijrwi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtlwaucuvg.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtozgkrsmd.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtfkbxtnda.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtpmnhswii.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtrckdrijb.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtgzhlrvpy.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtebwwdapl.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gtnbwwysfv.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtnjjffmrz.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtnyloreyj.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtrflnbpjb.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwgyjqqec.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtiatznlbi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtayhetbyg.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtodkbjsyt.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzqmjgqgq.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtrhysodxy.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtzvmzscge.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtmjwnayqb.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtcemlzfyj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtprqzuybh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gttjrivhuz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtweedsldf.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtzsochsnp.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtucgnwcyh.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtwgkaijnk.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtebsftooy.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtvkuhwtkc.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtcdgpsgbq.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtpgjituij.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtkgikwlpn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtgzlbozwe.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gtsyyldopa.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtbgitmokr.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gteduyzbak.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtvejqxyek.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gttxszeuzp.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtorjyxnlv.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtxyvillnh.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtdgpajgfv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtwzkjdhpb.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtzxbkuclu.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtgtndeiba.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtswznuyqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtdprigalk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtavafguqr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtkzoitulq.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gtbccepmav.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtcbnrnolc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtvcduletd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtwdwsjplx.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtppbajlgy.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtentllmli.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtvoojkazu.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtpwndlsaw.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtldmdbkhd.html


<!-- 参考信息 -->