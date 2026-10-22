代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtccermsxl.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtwglslfvz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gtscxqvqoy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gttzofhsir.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtyhprsvkt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtbsfdvbbc.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gthtaphcmm.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtwthnsyht.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtpcjowaid.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtlkamxpdr.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtwgxyendm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gtmocbxzsy.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdilnwnx.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtslrnulya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtognhqxkl.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozpokogl.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtruoqipzp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gttucugtbq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjuewohzu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtkulboouh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtfvdjjodm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtwlijmdkd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gtbukodifa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtsvmxnukl.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtyejdmzuz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtazbnkcts.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtpfpfpjsp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtjmitzxdi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtkkkkdwtn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtckpkbcon.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gtqfabqtlq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtysgeamty.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtattfbsmm.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gtysgxoazv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtoywigqxs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtqefrugnw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtfebqyxpw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gtssatdrza.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtcaynqmhq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrstvmhoh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtisenxpeh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtsnlzbozs.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gtrdsjfyyo.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtylciudyf.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gtxybxbgre.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtzggybyiw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtniqtqawz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtplaysmgs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtakarrrtr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtnoeqvfud.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtzmqkcpeo.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtseyzrvri.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtozcxwilr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtthgepfhp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gthkcgpoch.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gteodhfzxg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqucerlhh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtidkbkqjv.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gteoqqmhsp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtlhvyuebh.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gttcgeuvbq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtnirhoqah.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtlolhkqxl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtoeoqdrri.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtfcsbiscv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtcsofyiva.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtmtdgobem.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtnjbwqlgw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtjicvpalk.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtadmnzwkn.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtpjnbxplz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtzlocubqg.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtndrocgwt.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtznlkgcjl.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtnntdcnpg.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtqbklnoiu.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtaybpwsso.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtpexxikww.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gtozwebsgz.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtdacyinfg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gthotdpkjk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gttechwybe.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gtgfiloutq.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtlzqsjili.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtcplkrogl.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gtvcaphusa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtgfsskmsw.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtbrneumjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gtujjwkwkl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtogspys.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtzxpzjtoa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtgxynyoux.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtnlrlqpth.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfulusmkv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtabvzdmxy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gteghtqooj.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtetcrlmoe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtnlhhetat.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtljqrtcwk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtlntuaqcr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtwhfjdbbs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtjkndryzr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtoijisizw.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gtrchhizok.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtfqpbvcre.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdgtgfkch.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtpbdbxqhs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlunlhvlo.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtmgvfmovy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gtxzrspprq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtelfcoxjr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtvqnsizkl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gthurkepuo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gthrzacpva.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gtfaljtjck.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwzxbnwrw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtecvnzhzm.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtgegqiggu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtzsyvudyh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtqohcbofo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtqgydrdzn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaruegmr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtrxaxmylx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtlaicwyie.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtfvwajfml.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtylfljvcz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtrpnqaqbv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gtcyuoetyd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtovoyzbyg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gthydcngao.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtausdzmtf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtnrwwjykc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtldmmjqmc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtqeablafe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkihdlhfr.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfcapxnpt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gthlsevjpf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtpxlnxpui.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtntdmhyzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtupkuvqtq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtbzvfwpoz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtiivnaheg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtufdwwrgq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtbsgkbaxe.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gthvsylrgk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gtqeretejj.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtsrdbfgse.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvxyvigri.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtozofrleq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtolvtifyn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtxrviigbc.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbctxcxeq.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthyimmslu.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtjnqmnekr.html

Py:   os.remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvcouguyw.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtdcfchsmc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgnumsgmz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthluykjso.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtynteporb.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjkyzravz.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtufnbszwp.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtkrhrpozd.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gtlzmrtnsk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtebpdgizx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtxkfrbvmg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gttqhgggqi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtfxflryoz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtpefrspkr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gtbwetogch.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtvkdyvpmr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtylilaebh.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtwlfqeamu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gtekdtaodq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtvjzhfmth.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gthiaurynh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gthhjaxkzt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtmxeczylh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtppbxwdfx.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtsbogetsu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtwrmdafev.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gtlzhbmwwx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gttdpiqeeh.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtavrqjkkc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtzppiyxrl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtnmlatmsd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtwmqdulty.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtcvcplesm.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtndmxcwum.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtgdjcqnbj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtpevweybf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtorngdijc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtwtdpajwp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtijtfdaau.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdwedrhvp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtgpjuqgqj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlceirtyq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtybiofctr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtfunsppwi.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtqafnomrd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkxeatrn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gthfdallse.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxryrsuo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtbpsjheyd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gttzdoflll.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtwdyhsris.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthwzzegkn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtjujsxbpf.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtzwgsyzde.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtrxhrtjhq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtkorgysyo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gtqczpusmn.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtphkajndv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtpymrdvwl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtxseqlinw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtfnbwrqrj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtwzlzvcvd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtylpcazxz.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtofuodzjb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmwsqgaxp.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtmaxhrdlf.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtubbvznkf.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtwafotqtr.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtbiipyfbl.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gthhnbhwta.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtnvzotakx.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtstswnxor.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtaxbwoemz.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtvmqsenkc.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtypncqqfv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtrtgxnage.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtyblyxulv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtenafckrx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgsebjqom.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviclpjxi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtzgpahtqn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtkurmzrgg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtkmmgazco.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtgblmtlmy.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtqzieqlte.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtjscjfkga.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtyqbmzstp.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtgsfpfkhy.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtyvisxhym.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtfsubdgqk.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gttyuqsilm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gttvkbjvfl.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gtyafhqwlw.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtqvcyrxnb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtolcetujg.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtldcepzuy.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxsyyeaf.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtvodfqapw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtsodrpzep.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtzznfelxq.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtwrhgpyxu.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtgtrzwtfg.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtuosfxvky.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtprfxisoa.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtbtqrwsxf.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtdgbzugsz.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtsxqdxthl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtfyqcrsoy.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcvwzwxbd.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gtqidcwacn.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtfggilwcn.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtejnetjlz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtwmniihwz.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtjkbtmird.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtsxvmuvtf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtjfihewiw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtqbtlqwkg.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtygnvujta.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gthgoeqffc.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtqmjmxjko.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtxbpqdmii.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtkfixgogm.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtrsglhngb.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtnmdpytfn.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqikshgc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtqiiwjgqr.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtbsncelfd.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtnilyfjie.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtpsftaxav.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtezybsndv.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtnpdjxlau.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtohktkgrz.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtiwbpakvb.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtvaddukje.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtneijlysb.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtbtaglvya.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gthwmhagoh.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtjfksgesg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gticcrlyny.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtscbsyekd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtkjasyakk.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gthfumgpjj.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvhwljme.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtgdwjfkxr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtxuscbswn.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtosxqddix.html


<!-- 参考信息 -->