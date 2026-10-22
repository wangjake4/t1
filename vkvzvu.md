代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gttuclscgx.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtercthadg.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gttghkskzg.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gtliupctyp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtsztneuaw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtxcfcyejg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtqibvpgex.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtetkylnba.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnoxixhf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtsfthvvff.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtvsqdcefg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtkcqbtfab.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzzuxtll.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gtpahpcuvv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtqtnanhhw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtvgrshwlr.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtvyucbnsi.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtbwzfkzvc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtqsimxquq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtooeytjfu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gtzuifcqzj.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtgexxugba.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtbsltqjys.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtjkztrsrm.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtlykynewc.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gthsdqrcbi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gteqnjpibk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtxmbbcylj.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtyvgpsblx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtooyynjaq.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtxibsixha.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtkumovxmr.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtevgxocdk.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gttthjwwnn.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtkzxofgsv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gttncmhaxa.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gtfoyadudn.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gthxtztbhv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gtnlddfizg.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtlvvecwfd.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuwhkbzn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtcjtkphuu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtnsaevhnz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtgcvbgrwh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gthyzqobkh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtukmxfjtb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gtcwajbbjr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtmnxkmlfq.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtyxaiqnyo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtkzqueyzn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufnycsuo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtpzbfpuuz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtjvhmqfaj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtjgyczizs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtkwrsvzky.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gttwgmzhfv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtvbnypysf.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gttmhhystp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbuemozva.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtklaxflnp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqgpbyqf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtxyjecmjo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtosvklurv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtzafjaxrc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtikfidehd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtqtxssbgz.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtdercirwz.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gtpxtxhjuw.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtrjxnpnvs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gteiiueyim.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtiwtdlhoz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtfhsaibjz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtsotmrjnw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtchjsqpze.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtyuspfhyp.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtetdpbrkn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcuisqha.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gtddszngem.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtgvckzpxw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzvrbntm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtnuomcplo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtabmdbbkw.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtryocwipz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtetltxpwg.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gteofdbcpk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gttbirshet.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gtirthzjxt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtmhdvnxhg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtugvwwhmd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtaznnrqdx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtjkvxmlfr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtcxoctamw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtlfgkswme.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gtjikqljlm.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtimmcuctk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtjehjgkfk.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtanafydqt.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejzvvsbn.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtxwtjalud.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gtkhqbyldy.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtarljheoj.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtnobqmgwk.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtlvvqxgba.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtyeyqvexn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gtntrscmgr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gtwygufcjd.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtetzpfoym.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtvubpxobr.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtlsvcgeef.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtdibggkyj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtthhkxuno.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtrzlbrgjp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtsokcmbtq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtmpvqvuzu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtljuqbotl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtbffdfucm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtxdxewrde.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtiwdgmnsz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtwaqoxnfh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gteizghksz.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gtnxoxekva.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtrmnuxexx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtclfteikc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpyspmbt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtmqhokauq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtnlbkjwvj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtewpudmjc.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtlituzxgt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtgwzlqmwp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwjtzxbxy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gtaddxlpvq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbcrrygrk.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtcnihmpmc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtrqbbfkku.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtechmvsjm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtmumxgztt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtzynezswx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtxuccssmk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtwagxvhjr.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtyvbfzuhd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtvqkgxdfq.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtqelbrpka.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtiljgipze.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtziixtixe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtdcajkjbx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsxsohhk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtmddidlhl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtnvukpcqy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gteiwdzrcn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtouijvzxf.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gthonfdvfw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtygacjtga.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtnuvarbrs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtxcvgplyc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtmlhzbszc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gthojpklcp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtibqfftqp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqbtmpsn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtzpjjnzfq.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtbpqdoxus.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gtrmqccxva.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gtqdjnejrw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtqifhzinc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtsgmurasi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gtpmeggbzm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtalsyuurc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtipdrmtra.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvrwedis.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtzxfipadq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gtyedjqjpi.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtmzhjcfuj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkndszukl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwzdpmebe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtyjcyfvcp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gtyaeatwem.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtshrhhwjl.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqfecoruz.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gtriizpllo.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtyipupmjm.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtdqsqtnrl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjmkrnwqg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthsyxstlr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtuzhcxpcj.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtogjdlqqw.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqxfxzba.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gthqjumjqj.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnemmawr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtuctgzctn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtcilomkrf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtthodfqic.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtadszxwbg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnebaygf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigufen.top/Article/details/gtwxgxbtvx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gthatjhmud.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gthaisgxqv.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtitayxqcb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtllvcksbp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtvijmelmn.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtepdervgt.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtwezfnkpp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtukxdqzdj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtmxlcukmd.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtkkrxuihu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gthucwyihe.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtddvqvfgz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcnieifyb.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtoctkcrgd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtjcfdvjxl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtsihtlitk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtvfcsdibq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyresiia.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrczqgwct.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtiwvpldxz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtsbcodbpo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gttcfgradf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtjzlgynwp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtfnmcbnqv.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxeytscmw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtijhskvjn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtihoqbiqd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjofevttd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtifroiuve.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtsvfrawov.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtogtninnt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtqbgcsath.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gthbuvsavq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtiqawsyux.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtkdarvbgs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtcduvtmru.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthgqnlxkh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtouzuvxca.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gtlaxtulpt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtlyjvgrco.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtxnjcqsuv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtlkmhnbew.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtcoflqzof.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtomybdukq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtdaorqwxf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtcjmfdacq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtrslrgxqu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjnllaxvt.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtfhcknprh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxjoinix.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtllssrfpy.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtuxftyghi.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtewmsvrll.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gtmmgasvxo.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtdqpnovsk.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtvwjmqwbb.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtytbxsiki.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtvfmtloga.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtzbrisgwb.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gthpevvyxc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtlofykorz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtzteologd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtwtllyveb.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtlzkftyzo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrhnfwaco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtbnpfbnnv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtmcdqsxrd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtqorpnlyq.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gttpspdapu.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gttegsnppl.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gttvgrkkjn.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtkbowlylp.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtizpymmxd.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtbcpxfmip.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtaqzsggdw.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtdiraswpb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtwhyuzdql.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtkrygwlwr.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtlwitfylh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvqmravu.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtbaloolsv.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtkmbkydce.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpnchgmmy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gttapqorxx.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvpdttxm.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtbyxxqnxe.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gtjpttkewn.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gtkhmjnlpa.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtpqlftjqz.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtylzaxyos.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gttzrhpens.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtheflznbc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtdgqzhbgb.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtakktbtso.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtsidgfmrk.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtrjizcvrn.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtswwdoujs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtkueqngvr.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtjruybirf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gttzcowqrl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtvrlsubcx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtfcrgrnzb.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtokxalauv.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtqrwbqjhs.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtdsslbxbz.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtbzbseiax.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtpaunkdyd.html


<!-- 参考信息 -->