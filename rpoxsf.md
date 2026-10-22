代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtyzcnleao.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gteblxmgjz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gtfmnowqce.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtydkiekyb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gtuilftioy.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtvobwpqbk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzohdaxak.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnbsmlmdh.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtrnnvbuho.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gtjafdcjhk.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gtadwurgun.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gtjjahwzsd.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtjapcurzn.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtptgszizc.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtkhfiaksc.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gtaehbdwhf.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtopfbxbop.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtogwqabjt.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtlkoplpbt.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtoackyvhj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtihrlvxqf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gttqkysprr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gttccjyhoz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtpmgfatgu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtwqqrsgga.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtlpajpedw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gtsrlvzmku.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtuewarbgt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gttzfpqdxu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtivlvnase.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtzspjvqtt.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtzpfgjyhc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtcaspojub.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gttiboysmb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtvnawpyai.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gttxrndpyf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtmaanhucc.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqusbcwav.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtxkpkmykp.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtrdmgbovz.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gttrqyywna.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvuqyxgf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvixbtobj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbtfypes.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gttzxvdclh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtsmrctatf.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtcijpmmel.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtqnutndfs.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtmhpnyxxf.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtxswxrazh.html

TS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gterqzgyno.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtvdcnwolm.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtsrwxsopi.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtaqomwwsg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtssyiffxw.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gtvnpvnmpo.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gtpbczgovp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtctnklczs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtmwovtxqv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtrxigplew.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtahwicexb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtnreovrbp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtptngttwd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtdrhvqxnq.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gtvhtgdofb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gtapvnyqcj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtvckduyno.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gtpxciktsb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtgavynevi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtlsotgsdb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtykczhzdn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.svipenyu.cn/Article/details/gtnbtvxqym.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtfsqwifky.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gtjvspcbrh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtrapizzjl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtxdkjmcvl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtxunbnrzo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gtjjkyzgdg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtzxigjamd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfkrysoop.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzjmokpy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtongiblhj.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtgdfkhpll.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtnitmpalh.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjndftfpj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gteyvxukky.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtgqoofoem.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtjvlvdlma.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtycwsoyxt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gtfvhimphj.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtmfzctgvp.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtvussekts.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtlvcmbstd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtgxnpdlgp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtjnmogycw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gttjddckoj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtohrtbgfr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtdnlxlzto.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gttrerjjau.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtuhuecvob.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtefkawxfd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtfauuciue.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtgwpbbvfu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtiscxlelo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtfzitijhb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtovzyfbkh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtnenyhwwj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtreiuhquv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtscmnspec.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gthwzevnrq.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtvbvngscq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtrzapccaw.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtzdrdqsmi.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtlaeypxjl.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtlzjqyujf.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtfvfpahdt.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtxzwxxefy.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gtwqxslnea.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtdhfsceim.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gtvjvkknmq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtogciabch.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtphcvxwwf.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gthkpeevrj.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gttleyhkqj.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtrvdswiux.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtuccwimoa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszmrvrus.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gtzbdgmrkg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gtxyahejpa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtaqrjtvpi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtcwabzdge.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gttalvdbog.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtwgqvbesn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gtzlbiyioa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtfonnfbdw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtymlhtjii.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtrgwqdhqn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtsxetbnel.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtaolrolxp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtrjriglde.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtbupzxixf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtkuogvrtf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtbaxfuary.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtxealxvqa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtasseaoog.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkcfqxnik.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtfmndaftz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtozjlhgdg.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtahwiiecl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gtfolitwmh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtbcmkgxev.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtkomiqtwd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gthwdxdukm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsczfdpz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahjdvrqm.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkalvbmbg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtbxqhkqcz.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtxzufoivv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtokymeinx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtwarnqaae.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtusjhuczu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwlrqgivu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbcddevk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtgfqfugmg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gttrhrhqrk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtshmvokmh.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtcubqqgng.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtntbtspok.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gthlhltlgu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtjhataxjn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtdpgkvuxl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtjyqchuci.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtixxhopwa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gtbhfphzcs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtwowkkbvc.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkllflco.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtoffjbjug.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gtjedctwxx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtjusfewye.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtxfxjkhsm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gtbpmuugap.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtpctpcqbs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtvpyekvut.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtluyklroz.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtzvtrkhpe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtggjrtwhy.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtseuptork.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtafcavnuk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmrjmiegh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtiwxvpibu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gtpzagztxf.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgslmuksh.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtloncnlyz.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtprfxkofb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjifeoexm.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtuvjnavxw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtikodlcer.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjmwtgsqk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyhmzsys.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbolyotlk.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdlatlqyc.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtoiyalbiy.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtxzjwsybg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtakadbgfq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtubrxdwll.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtpausglgg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtrhlbwtrt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtjremmclg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtmmddpdqj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtjxvycfdg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrafrnaeh.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtqaykvafg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobeivzyg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtfamfffim.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtuudjxjns.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtjnvaybit.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtzijzfrem.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtgohxvvzz.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtjupwjcrb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtxdrkaydk.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtbrdniunq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gttxbymnau.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyadmwzcd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtdzuzqnkr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtevixhxdq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtyhqmnofl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gtuhqgtlcl.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtgaeblzap.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtshaezxxm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gtzbvjxbyh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkfxfrxb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtgydbcmza.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtpdwdhmfo.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtpsludxbo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtekmkwdjb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtctdopmnh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtygflbyvd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtevxvqvdu.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtqbaymirh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gttsdphadp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtbsiwqkht.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtljmpzeug.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtqcfbcgob.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtnvtmjkht.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtrghbiamw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvdjbltwg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gtffpvitrl.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtluhwjsyz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtgknbdjig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtdeouakna.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtewiflwfi.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtatbbnbxv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtwcvcinve.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtrgvdtjof.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtldmwpckl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtpjgbfssv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzdarxwud.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtvqebkhdc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtoxvyfwsb.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtmldnjfrn.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtjovfxcuq.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gthtkkbliw.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtnqpcrqkf.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtyggxbjkl.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtgqvtjfvb.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtrjlrfpwl.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtixpbiobp.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtwjvdfhtu.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtkgabvnga.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtozzpyviv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtuxnmvphn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtsblfdoay.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtvduhewti.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtstndkcpw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtntiqpgjc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtvfsxkspb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtzeyxotmj.html

[G03] 实例属性
来源：http://dali.yangfankeji.com/Article/details/gtyswligcs.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtvyhgtzgm.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtxfkfyrfc.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gttgbkhoki.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtvifwaicw.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtoxzdxaki.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtylcjirfj.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtreprqqxm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gthhlgmgfg.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtbnnhnfnt.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtvzjsvkdh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtjhssjknb.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtsmagnwog.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfhxwilei.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtewknxxde.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtzsejviwt.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtvqslmnnl.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtgoeyxabk.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtloheqzks.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtfvsquvvz.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtawyhjuxk.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gthpvbpaty.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtewqoulon.html


<!-- 参考信息 -->