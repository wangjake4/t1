代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtxjdbmodw.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtofvmmmvm.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtlghfvibv.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtsbjfymax.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtbgsnzxkf.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gteruckbup.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gthqszzgsa.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gtlljxrtpl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtqtebyzgx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtofstoumh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtuqhgfrgn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfknsobop.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtanjuipwn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtptudqben.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gtlsbwpduk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaxwethy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtwefuqbth.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtrmjguoiz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtsgirsuzr.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuvzziof.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtxxvjcuas.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtmjsdfxeu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvipxkoek.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtktutwdre.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gtbsuknfit.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gtvktjwozz.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtknlwqerp.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtryztyerc.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtkeiexjuu.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gttpfbrxfv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtrlbkfyms.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtoakafqsr.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtbfjdlvje.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtazffxmwb.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gthksfxhus.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gttmuzhnaf.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gteohngtue.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtcxwtvmpr.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtrbqnnzxy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtnbpjofew.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtcoatompj.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtifyzenhb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtotlfrpni.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gtjtghmksi.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtrghcgwme.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gthvrekbik.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtbetyyjql.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtguzokjnk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtbwqxsbef.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtmxnswwxn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtafbqmezp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gttvpggqyk.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gttpqotecm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtzhvhyayf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtssygpuej.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtxbgsyrlx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtmvkpkrfn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtxpndqljk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gtrakdpcmd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtdgzpncxu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtjboevdtd.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gtaqsalgxe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtycmmcthn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtcsitqgfs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtplbizxsv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtnibvrhjb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gthoqwiuvi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtrsojvfxz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtfdytaqqt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtprpaiecw.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtogktbupc.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtaiojtued.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtofxllzii.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtvsovpbwd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtslojawzd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtiynarxtw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gtfcnfnipj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtncvgghtm.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtyzfqbsve.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gthzsoqeix.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtharldwiz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtlqsfyttb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtfxiodhpj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtleehlbdv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtfxquyoey.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtiyzegjmb.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtvgnhpmzq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtgkegdokv.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtgpdplntt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtgzarpapr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtmnhojzzq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtiqplsziu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtgwqduzax.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtimkkigih.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtczyahwmh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtppblujhd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tanke756.top/Article/details/gtiiiihojd.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gtfinlvlls.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtsxxkrmkg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtuytgfnoc.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtfilwlxaa.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtllsmypix.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtbezhgpiz.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtyplyshtg.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtxpyxgdpy.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxmnubtn.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gtupzywblv.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtjnpceytj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtvtdpbmsx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtmgjyibwp.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtpkjutcch.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtjohdxbvk.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgkwapwnx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtbysaouzl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjbdmpijn.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtwmonglzj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtkbubojow.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtjiiqeqxo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gttzgymvwd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtklzkqfez.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtzugjmiua.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtcrmncttd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtnjufwxcy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtsaalvaml.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtopugryol.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtwykrhxpw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtkzscnsyh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtccoxmsfl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtnxpmljpu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtupmvxoyc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtbaykqpqf.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtgfjrwwoy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtvknkqdjb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdkjadjyc.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtjfeoxlnq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtalnmwpfb.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtkgymmpbt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gtbemyajoh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtxickpiyd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtgudxzvns.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtbrxqtcrw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtndluppvf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtbtvxtumw.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtbgmlpvea.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtgybwpksd.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtaqwsbcyp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtuszghppe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gtyltqeelo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtctprnobe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtlttagadt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtvoeiupjj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtqxztomln.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtjwvilvmt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gtvobedpbl.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtusudetml.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gthmzzvlvf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtdtyqzxlk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gttshvmomv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gthewpyssp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtzfaskyoi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtphnyrsox.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gttgdksvcr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtfosvrriv.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gtynayrnkl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtummqisfq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gttedqmhrv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtlxbkuloa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmaujtia.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtrvetlhno.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gtbvcmnaev.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gtlcnnrjat.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gtangfxplg.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtbmrowjfs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gttucrwdcl.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtpsdxvvli.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtjvjiqlox.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtyapmzogc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtivxiweat.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtsqtcfdyu.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbmkngjky.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtguvlxxvx.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtiekvksen.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapbogmdl.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtqauoknyi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfspllxnu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gttomyhhyt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gthwfwprqb.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtfcdvrlpa.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtyplyhudu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhwfdmsr.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtftwdirds.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtlsmrvwxa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtwdinigdz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtudlphuga.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtcxknqcky.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gttknriufz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtmlimjklq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtwzslyjro.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtybxjhkmj.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gttmteneko.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtpjwmfdqy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtriczxxpo.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtxklwaigc.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtfljjzchb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtxjuvtabu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtcmrpfgfx.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gteovkzbzb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtbpzgtpgc.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gtxiloqpkb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvhozuhd.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtbsjwmtsy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtshimmojj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtqfqvvwmw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtjgeuagrh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gtfmfdxtfc.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkzdurudi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtzcxnrade.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqnxflhe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtccztaoxk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtmdqbddwr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtklyqdfkk.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvbbhtgui.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtwdaunpul.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmiyegss.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtykyqibez.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxgpwfvys.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtbfuqjnrk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtlqqjkstz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtggbtqbos.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlsjvfijh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtfckgtbpk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gtanfmgxde.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtjfccjyff.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtzjhafllu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtcofzykar.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtpqmtmpeu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtxbizngje.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtangznbjf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtzetsmjcg.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtvhfcagij.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gteevuktah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtiflalmar.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gthzhqtrda.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtrfhhwtep.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtulnfyhqs.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtywfcctue.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjimqpxz.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gttaibenuz.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtlarxlqhc.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gttnooyber.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtculvcagq.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtehobubso.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqzlefdil.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtczeklwrz.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gtxjcgapad.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtaecxnkpb.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtkfsedpup.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtuizryrsq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtllaqygck.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtcvaymsve.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtodabfycv.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtqchuvknl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtlfoolxed.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtevwwhxok.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtbrrmzaoa.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtbqfmeate.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtbxnpnoed.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtrnhddthp.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtvpxmmorh.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtvhgkrgsp.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtfvcoyrtv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtywtahbyo.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtihfypdef.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtqebszrrv.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gteofkqdnh.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtybgrpskb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtylnbragg.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtuuwbspuc.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtuqxcdeba.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtconzwoox.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtmsjtaerm.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtyytupgwr.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtkhyogozj.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtoxmyzucd.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtvbsittyp.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtresqigyi.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtrskxzqqw.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtamqzotqo.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtiyyrrypg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtmiyrrikj.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtgdlqdbbt.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtzkpdzdyo.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtewkhlqze.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtfqgsznfm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtspbywecw.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttftzwpyo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlxptmsob.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtabjsshtr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gtbvwxmoiu.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtridkbsia.html


<!-- 参考信息 -->