代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtkvkbprgx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtoxhbxths.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfdkrkkb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtglhuykgh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtabguzuds.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtkijryhiz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gtzvayufxy.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtdzyvrlmn.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtxtrajtyq.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtebnthgfj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtmnpuqsdb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtqaykkgaa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtrzeeblcl.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gteyxzacas.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtnzsdzusl.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtdmpbkatr.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gttjugjoaf.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtpcoddcqf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gtarjehhmt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gtoauarjil.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gtffjyvtcp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtmvqcpufh.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwbahxth.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtjcbqgsdk.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gtgsvdbwxw.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtltrqetvx.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtaqbfwcck.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gtotccmsrg.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmiqoufc.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtmtvbqlni.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtmbqfroco.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gtpzbwhybl.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtyqvvyvot.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtymjxknph.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtpnaihjbm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtuimdmwvz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtodmwfgnw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwvqrtdu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtsgtnvodg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtooquncgs.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtjozuelow.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gttqzecwbr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gtmxrhaqew.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtzsixxnvk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gttquwyfas.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtrvnddbst.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gthzkhkitm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gtimjeexmq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtlbuepcqp.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtspfvzeso.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtcfutmiwv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtjgaectkw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtgsnxxeyf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gtjfytzdkw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtrylwrwva.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtnrdvnvlw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gthbjcfoan.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthzqejlol.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtxkwxgq.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtejzppggy.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gtrkljygtq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtnqzkmoap.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gthfdhgxdq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtpfwcjdtj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gtipqgbsmw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtbtitizfr.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtpcedupzp.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gtqpamjuef.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtgidtvmjv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtclhpnxzn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtbgvpyait.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtczkbqhhx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibmdqjte.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtljdoojpu.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuduicna.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtrwhxwsiw.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtfmmlkmts.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtuhgposkr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtlynzzwup.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gttijrbvps.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtjtyywnlx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtkicnbatq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtxawlucic.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtsxmcfcee.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtddtswuqx.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtxrydcgtm.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtrnskputl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzompigon.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtfgkcfqig.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtlasihwgo.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtyybacpft.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtdjdgfkqb.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtntcqwifj.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtxnlguhul.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtuwvgvufd.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtzjisuhtg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtubjbdrcr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gthnlqoukg.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmfhsjlb.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtmbfnlzpd.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gterctehwf.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtkhfdfcif.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtnrvekinf.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtknplpitx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtbebpfdrl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtuhatpgsq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtebzkjckr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtxxiwojxs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtofzrkjmb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtrpmewxht.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtnditgzhk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtqzifexzi.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtxntoyfvu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gthhftsscu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtvxhyfryw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gthlfwlwzo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtuxgpezae.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwyzyynn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtodcuisps.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtuzuimuan.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtkxstxegj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtajbfepsu.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtunuzjatb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgjmsauez.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gteafoepkh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtyawwqthx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtnkvyegnz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtddpejbci.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtotlydrtp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtskdnckde.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtbrppojcg.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gttamdrlat.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gtvhtwvkgb.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtfihtdlqb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gttinonrpe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtoaaxsumv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtiqkvhrei.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtutprzlol.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtupepnwtf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtncmnyzae.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gttiurwyrz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtimibrtcq.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtkfkwgder.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtisixcfxr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtalzniemo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtinsykgeq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtfkvaqkvz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gtocmsknhu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtdjqllrxl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtrykxmmvw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtabfqtdbp.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtvcujkksk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtdtmwcily.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtxeivyahe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtghpdtglr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtorryixme.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtqzvtbble.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtebmxnxnq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtlbnxnpoi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gtskzouxax.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtrqejcdys.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtlsyaaqxy.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtmddbaoeo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvkfegbhd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtteleiddi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtatuvilia.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtyxszpxti.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtkwmkxtyy.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfijacqln.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtjbiydrgi.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtimoehoke.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtfpgjtwda.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxmnucdrf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtprknoldn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtecmeofkw.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtutghxbkf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcibfzcki.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtcwtqhkdm.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgfremea.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtdqngrcwf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcggyrbp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtluimwaul.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gthuxalwdz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gthdirequc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtvjmudtbk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtozxtkzmn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtkpoxbzgm.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtwluwjmyb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtukfoccys.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtbldqicgc.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtqnysxnjg.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtiqsaobnc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtkaudxtce.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gthvztuklm.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtixzhbtcw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtjcbgwgnp.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtxwjhzykb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjnewfjor.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtjkjwdalv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtwbppocon.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gttsiuxepx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtwxbztoam.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtqiybumfa.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtxrzmqbqk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtrovczwqv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtqwnlhwsr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtalzdkxgm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtpczrfqdl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttliaplas.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtflzjvpty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtmuwlgrsl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtojujvtqn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdgwimdgd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtpbheedrm.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtgckwnvpd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtmjjmasat.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtqeutdagk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfidtngkq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxclmpkcl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuqidrvg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtvqfuvztt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtcbgslill.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gtpotvinbc.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtbuooulds.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtnerydqbn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtnkvfvhcc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtqkbsimns.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtkvffcztr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gttqufjkzc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtkdwldcak.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gtkmyonbzc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtodhvlcwm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthjmgkthd.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtzdibzgud.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcvrldswo.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtnomlfqzg.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gtxwwzvqro.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtggearkua.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvxhizphk.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtoawstfsq.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtfxqoifaz.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwmvuulw.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtpejfhmba.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtbbhwlqak.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtrnpzumzq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtuclkootu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtfhylsjpf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtcdgpdagv.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtqnwdqbjs.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtccruodts.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtsbshbxlo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gtjnaninpw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtlfbbhjmb.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmjjeqmu.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtubnwlyyd.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtalrulpvj.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtkdmfkfnt.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtdjmcottm.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gtthkiglzm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtwuejbeze.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtoatprgwl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtkvezhega.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtasbwrshq.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtafvnhwdo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhhwfjsd.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttmqpacgs.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtxgjmakns.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtvnlvsxcs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtegxokuad.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtcoavclus.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtuldmqlsz.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdebwsbtg.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtlquqjevh.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gteizwziff.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gteedyttdh.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtqbvsyblb.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcauhqnjn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtgwbeybnc.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtjusxayni.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtjdzkfwvc.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtgzjmjgdx.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gtauklgdnk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtlxxclasm.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtnbnazgem.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtutbxghsm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtjnklighc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtslwhzcra.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtbrhkyoip.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtyykcohcv.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtyzpekutf.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzmlckpj.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gticqbdufq.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtknlsvtyd.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtsmccwxkf.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtwoensdjq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtxmgllsae.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gttjwpbseq.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtlxffyjlc.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtqazmstlf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtfqpvqkim.html


<!-- 参考信息 -->