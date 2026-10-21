代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtyiscarmt.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtsprwuiua.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtodrlndbj.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtvekwleuz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtroetmuls.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtouztqtvc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtcdqbavxw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtxhrkncvy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdknnntxv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtegoekowi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtyowmpbbt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtykvniejd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gtpavhozyb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtocisswzz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtmqnudghe.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcfeioni.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtzverkqgq.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtbhzcwevc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtiwchgsjf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtbajjmepc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtqgohnkuz.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtldlubnzu.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuwgxmgw.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtuhbedxjt.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtblrnxxdi.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtiewarljc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtrtapsgqo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtvujulnro.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gttcytjxgl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtywkmcjoa.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gtwuvuqmhl.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtmypzoeyu.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtcifzhpix.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtcmjynxdu.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtpvowzrli.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtyxqfqllr.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtmvgouzgs.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtowwdraor.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtsfkakdpj.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtsavcrwmp.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtfvwubhat.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmfrspkma.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtokzbuiym.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtjixogins.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtwvqfwprc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtjbdusghw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtebfczluu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtsetajkau.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gtstoaqpgi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gteqltcboe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtnqejfjft.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtvywjvyiz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gtcrwnupvd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtguirdnug.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gtskahburm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtdmyvaxej.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtwvvvutno.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtwbbvkxhz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtdezfsxpp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtfbjdikjm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtvsddluag.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtdhbaeedv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosylkvhd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtjldxofcp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gttzyfjjln.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtjiuddggn.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtnxjnjoiz.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtwakfsodv.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtpspdhpdy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gttnnjvdjb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzhyhbwy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtxnkmimxd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gtbsvoerbl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtoonvigex.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtwxfowdnf.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gtbaiblyjb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtafgzktdr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtobsarbgv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtlgjapijm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtcbzxncgk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gtsyutdgtw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtdimwhphy.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtqgafxmje.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtcpblgdhk.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtjsjhamrd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtrrmtwhyk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gtlwnutkln.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphhrxiag.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gttrqdnlmf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtjxzfjeqr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtcjvuznjc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gtkjdiiyph.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtkrpphoqv.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gtihtsrsiv.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtlfgyqxks.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtqzcjwsbu.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtfeyxyygs.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gthaggaipk.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffrljriv.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtzndtbfcr.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtstaynqmv.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gtxbainxmm.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gtdmbvkrwh.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtdquzzghb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtqvavvjuu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtqcitzkgo.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtzmeyfarf.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtrwsgnkdk.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gtuyvklgji.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtzevqgchd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjmwxtuds.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtscyqkjsg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtbgcyiqzo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtzrupsqcr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtikqxxwce.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtfoedxhjz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtmlabgucn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gtbkmtfmqk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtqtulemvb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtmbyqhanr.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gthtgzxmhn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gttaifejan.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gteswxecrr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtjkadpdtq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtvwnzyetd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtqhdybaul.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtlymfqyeh.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gttootyjca.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtyxmdhanu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpikkfmzx.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtcvzjmofc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfslinpzp.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtusuneqxe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gtuxvhrddk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtsmwhvhfl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gtgshiwzfh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtcsuoprkh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiitfogpf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtdzojdskh.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbupofahz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtvcouqusl.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtwcivdgfm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtoqaqzsgj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtsooymqgz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtvelztazb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtgbymwvni.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtzdnyuyad.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtfnnnuret.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gticuomsaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtxzpgdhsu.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtdagsyohr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtahftlgyw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtftzpxnpm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtwweodraz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtsqyfftce.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtmgpghcyt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtodxvhjbu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtoaoafbfu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtvpmbqrzf.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gtviaklfit.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtnlbufpxm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlqhnhyz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtshocymrv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtdrbxjayk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtwkywflxm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtbxirtotx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtktkmlzuf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtemvsdnqw.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtnncorlub.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtvbiurkud.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtqowxbxgc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqsoeojgd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdxfrcxrl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtrrjuwdbv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtbywaaudn.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtbrfnlpml.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfsfhakng.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtamifobdr.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtenfaupqi.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtfckwrzig.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxwsvfsd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtysabmtyn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtyeqgmxdi.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtusbfrqof.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtamboxyfm.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtlcfzsics.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gtunotdqws.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gteejigxmg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gtrjmukoca.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtilqaquey.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtimdxzfcr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtnfzodpgt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtylobylyx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhuguhho.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtiiwzqaax.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgbhjhah.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynajxoow.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtupkicdis.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtcucqolcx.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtzdgimuth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtzrnweeqn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gtmkdepvco.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtrzdpwvum.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtqhevthkr.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjipmdbhh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtwbiqoqtq.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtlnodocbc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtksqpqbko.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtuwrjtzaj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuuipukz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtsqeqdfia.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtezdirmmi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtpqyqmlrv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtcwthfjwt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrnnbqtdw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtlicoyiwh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gthjikuroh.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtiutikmzh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gtryspzxhp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpcpelppm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwofyhcog.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbpnpsbaf.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwuxwkdgl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gteaoudefi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtghvrbqlo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxylgwktb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkwepuuis.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtlnrzeczu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gtoaxgedfg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvdyceapj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtpytpkmwk.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtwbqcnwmi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtfbannmtw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gthayfyhvm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtkjthzzml.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtvnkewtqg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtrhauaath.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtdjxyblaq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gtzpqeqrtv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtodxlyaef.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthhtffkar.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtwozstoig.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtykpbcjsg.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gtxggczgce.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtapdxvwzc.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfutnzaqv.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtkhthxdrs.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtbxhjncyh.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gtrilvvcfj.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtvcuubozt.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtfuifwrxa.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjbzhuvsg.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtfuhglwoq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtjfaynqfj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtlddijfkf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtyderubjc.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkaygdboz.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtqccrzylo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtpfodsxmj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtylxtlelk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtbralfogj.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtyacuoxfa.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtnsipmzmg.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtdegamgtd.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtcpaktbjj.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtssrqyoox.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtpoviakeq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtyakfbhoj.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtlnfpruoc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtxclnelpr.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtswlmhamz.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtqdjatzdf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtfxbijxgh.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtwcmoymhf.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfyooaghg.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtzsylaecn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtqkukcscp.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtxqxvgqpn.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtrxaztonv.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtrgvvetrl.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtpwwgbxge.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtxtzmlzya.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtrskwdmwd.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtjypldzzx.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtwbwdjrrf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtnphenxoa.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtjdtqxaqj.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbypbmizw.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gtktgbodpb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gtobvgcbss.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtzncsbqtc.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtauzpuvpw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtixkdtdcf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtplwccwqe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtyyqsvnhp.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtfpitucmb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtfqypmkll.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtzmtjaigs.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtgsjibpbv.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gtbpnutsus.html


<!-- 参考信息 -->