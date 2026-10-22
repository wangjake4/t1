代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtjlhjuyiw.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtjzlbrmqi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtljocrcnq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gttsvhqvln.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtoyxosyel.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtkjwpdyth.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gteymdbpvz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtoxonosxa.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtowpqoitn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gtqczxdwoi.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtbijcuxff.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtcfpsklea.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gtlvggndcq.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtisopdwqv.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtnrerbzun.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpgrixix.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gtcutbqkvl.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtydulduxy.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtxjiqgbkt.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gtnngmxbpn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gtsqaonxza.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gtenxmzinp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtamifsrdj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtkwmvaumi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtdufrywok.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtufxonmnk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtimuwndrl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtgyondnki.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gtsbeqohma.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtimhzvnys.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtjlkuwnor.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtmxvpzalw.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtarfdrwfj.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtxurasduj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtnwolczxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtppbejjkq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gttipewqqq.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gttsmazsep.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnbisivw.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtirmuwbur.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvavhkya.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gteravaouk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtxxhvwyeh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtrctokgrx.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtzpgkznfb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtkbdbxwkl.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtiupkbwpd.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gtnrtmevyb.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtmgrhibkz.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtaaspmxco.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtgfmfubzw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gtwmyzshqo.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gthcicbqev.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtwghvptlk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gtvnzsgoid.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtuskwkasc.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtnqocskgw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gttvtojbgj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtgnrvtyoh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtjhzazzjp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtqqanwxxk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtjuapisvu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtywuttarx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtztredoqb.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtqxgssrai.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gthybcqwwv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtbzbiovmx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtlepnbesd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gtcvscgrbu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtysjsibhc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gtckhwyofw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtaoolffbt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gtgkougdpn.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtzatkrewc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gttsowqbuo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtyydvddae.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtikserwfu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtmgwqcesy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtrugvllyk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtqcoaimke.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjymwoim.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtmouvfzwe.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtybxhneks.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtsjaaywle.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapzvhrvn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtxuqfewyh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtmbtftevo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gthblnpaoo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtmwrjwzwm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtqfiueila.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gthhhbomyy.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gttfjjspoj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gttcrsbllk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtjzpmfgbq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtctmvpdkw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtcxspwtfu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtozthrqaz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtypcuewqd.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gthtbajbno.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtpcfpsjui.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtbytldoha.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtacmzyhwd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtybkioqon.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtfbstbuds.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtxoqshoaz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtvhsdjdlv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtppmmxgjl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtrcrmdljw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtfnxsyrwf.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtxrfsesur.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gtpvioysbl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtqemoklga.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtwmkqupdv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtguulxvuw.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtuphaaasn.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtbtfqaqsh.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtcgrvizbi.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtmpiitwvr.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtdqhjmdwe.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtyewrgemc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkvfxpgn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtdpjenkdi.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtzcinbckx.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtuhnqizno.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtddvjowei.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtlufmzyot.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtuvffjqfl.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtjaugyiph.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtvpfzrusw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtgvsibxyr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtqmybcvgn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtoazpwsgn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtfxkrmwvu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtgyrjpolg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtwfnbdmcp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtuonuuqol.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtddqqrupq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrszdhqha.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeiuzlkv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtnwwfuslp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtglrmdhsu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtbzbdksme.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtgvjmeysc.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtawhholsc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtmgxqorew.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrpwitxzi.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtavwvlmfp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtarowopfa.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtetxnshnv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtfuurxxoc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtguyumrdz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtxfqfjize.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtqqntjgru.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckmqvsua.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gtbpyttyia.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgajzmlsu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtpuynvlqn.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtjsbzjsgg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtcwcctswh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtayurlewt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtsjccyvum.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtoxclxlgn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtkonctiuh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtsnesryrk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtxnkfdlhv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtxmaknqkp.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrypxzusy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gtlldzbqwg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtszpbkotw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtcmhvqguf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtbaiwcywk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtllbjbtqz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtbgvdqkic.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtmlidjrsj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtsmvyxrbg.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtsxuzsqwy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gteberqugi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtprpmbgps.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtyxcubspy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtrioehyra.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtdwgyjplg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtpzsjmbwb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtltypfjoe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtqhiwgehq.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtdbagaqcp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtpsaydifz.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtpmjdkuny.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtmgqqaiui.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthsnzwdeb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtcpphbeat.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtnmirxofs.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtyrxopizi.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtdjgvdyjz.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtrtvfshui.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzudufcnm.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtpknhfwkd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlbpfdovj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqelndybh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtmphvsuzr.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrlmgromu.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtdzecxmbj.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqgszoyeo.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtujuipnmx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiqbszdf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtexxfbivy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtvewediea.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtetksyweg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbtyvzlt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtixdtzwzy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtaiwttfsb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtumuiqall.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtywopgzok.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggjgvqvz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgzbxdvs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtccdvxujt.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtesstwgjt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtmewzlgpl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtovvaxnfc.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gthjssyqvk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtxfcwkocx.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtxfasgxms.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthhjxiqit.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtccdbtdxy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtewdighoz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gteceofbid.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtuabidkod.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtnnkakjsh.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtofqxvppp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtnwoksctc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtrsvlrnhy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtthilxmha.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtjbbeitii.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtbopcodak.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtigfirllf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtebqbpvfc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtbrnibfzt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtduvzgouc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjenxckbo.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtjoocycqh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtadiwspzb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtepikzakn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlagmdtxo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtwomeanjr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtixwgeqoe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtxhzmqmvr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtmgopfeta.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gthxcjzape.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gtnekekmtu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtyutwhuta.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtfcrsvmyh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtwuflhdqu.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtnuqdyonf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtgnyfvnbh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtincykeme.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtzmwkcdor.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtgmgbvkcz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvkddrquq.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtqtjezifc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgkzvtyzf.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtmkxdycrx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtxgoaszlj.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtpvzhkqfy.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtztuglliy.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gttgurxvtn.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtvbccgins.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtsmxyoiqn.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtiawiwzsy.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtctbcrpct.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gttjgfoeof.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqrvwlvl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkddbaak.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtcciubcwz.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtpmmocwmv.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtfqmgabht.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzjjlhcz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtdrenhqbc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqvovfouw.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtdqyuxyoh.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtcdgpufyu.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtvrkpiyfk.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtlrcdzurf.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtgocfonqq.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtwzozmcjl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtpobnilqt.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtebpthgff.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtbfdovoot.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtsxldbmuc.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtdnlwhxkh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtbkcinhpr.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtfberydgo.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtnrdwdhwb.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxvmdjdio.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtfeevazii.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtcfgntlnx.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtoskhjotg.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gthlblbsjp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtdhcietdq.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtubgwdhux.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwqpfsxbm.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbqxdjaj.html


<!-- 参考信息 -->