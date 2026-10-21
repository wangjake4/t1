代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtufoyebav.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtbtcplfwa.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtonwzvcbq.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtvdfntrgw.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtyqtowhxs.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtiqsyfket.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gthwaoujor.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gtaygzbfkn.html

Go:   strings.Join(items, ",")
来源：http://dali.sxryk.cn/Article/details/gttfujumzo.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtfnzgteni.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtnzpqhgzw.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtqjwheolp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtybsoesqx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtbdhuqhmh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtygzwladu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtljrafzpc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtwrisjjhw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtxmlqmwtf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtquxbrvnn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtghdfxfpp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gtiytuezsz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqmcmdtb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtqxaaoocn.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtoyfzbbrl.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtyfkmynap.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtdrblvpza.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtrccbiphp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtuquswljg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtqydrdloz.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtgttfwrea.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtsgwbsdzx.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtkrtxrzag.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtbzyvkvsp.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtrowkmxbx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtthfckcln.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtdlyxdnnb.html

Ruby: s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtnbbrddin.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtfkvrsjrn.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gttybtkvfr.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtxxjzscph.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gtqpvvclyz.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtsevcaclm.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtatsxdtkm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gtjfngahsh.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gtxsnpxkvs.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtnwqpqynu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtuuzviwsc.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtnzfgtkkl.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtodfmenhx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gtvaprpbby.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtkwicjvwh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtanezrlex.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtfwrmjftz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtqgkeddxz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gtljlbviqk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtpybioxjx.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtgkxabmzh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtfuhtfgme.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtucrzmhqx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtwiaqzsrv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtefrcrgwt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtszzvnnfk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gttfonwpsd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtbxndoxcy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gtuyctieyn.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtlfwunyls.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gtwdltxoti.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtnjftpdzh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gtybrkgftd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gtmqlogsph.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtyawfmgyw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gtgewvxokr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtovqbkgei.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtyjwvtdlb.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtbbtrjqdh.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gttvvtnbrv.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtrsedjceb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtotopsqck.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtcakqmpmw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtgurovaey.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gttrcszexl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtntaoepnl.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtgvegftip.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtacbptcuk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtytiyznoe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtapssphob.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaksyltno.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtpsiuixmf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtewetmbzi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtuxfxbovd.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtipehvnbt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtnwkzbrzr.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtusuxhqry.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtaffezsyw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtjgbtyydr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtimuojrsh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtvfgcdgcn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gtaftuvcok.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtrtbdxosg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtqyaspxtc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtbrnqyjof.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtgpsfsluv.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtctgnvlem.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtkzxovzhm.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaitoiac.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtyomdhcax.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gtwjvihxnt.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtotslujpt.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtuizjglje.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gtcmbtzyou.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtibrrsqbn.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtrfamgxik.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtphzuqhru.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtuwyduyhs.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gtdkbvpqil.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gthskxqgxd.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtfldrsawg.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gthsclwarr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtjmjxtsnq.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gtpgpwdctg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeqhtcgk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtvajsjehp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gttsxzvrpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtkvlczvig.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtyvhvwqee.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gtanhxdccp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtgsvwiash.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtytduwsqh.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtqjprenyr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtfucawfcs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtgzliojvq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtpxevthtl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtwrkeegtr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtsiuvpffu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtsqpbxvgl.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtaczdqdgf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gtpqyalggo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtikriruuh.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtukeeusfz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlewidegh.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmbapnohi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gtroulpltg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtsjnzqpma.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtymgzzcts.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtreoopyes.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtbjdtlydt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtrqzjviwg.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtthpniwxr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gthqkzbzxa.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtzkkvhkzg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gtidonvzgt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtydsnnnro.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtxnydvzpn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtuuookppe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gthmtuoafa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtbwoodjmw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gttdskdhzh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtnekdpclm.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtdfraknxn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtsahncuhz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtrfzetfnz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtfcodraxe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtkecwhtlw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtalqtlkuv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtsyplnyvl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtouihnxsg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcclaxzmn.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gthqteqjke.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtjfcazwmn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtxlghrawd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtphghvcgv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtsswypkcj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtifqqxhhg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtlcsgilcq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtpoupsdaa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gtpvgoqjfb.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtpbcskegt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtehdkuwdo.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtajbtxihz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtinrunpvt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmpvdeyjl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtxxirzwvz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtydjluhys.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtddaelsuy.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtapnxlcsf.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtxsdjcelc.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gttkrhpjth.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtsimgszqg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbkdgoaj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdqbiiohw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gthiimbuhx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfjujmbc.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtuudjtgdd.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtwepztczf.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtixpsvqkm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtxyamohgz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtclccazfm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtmmksckjb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtavlrrkgk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtfovblwmr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtgpiasi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtquwfoqwm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdwnspiz.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtjknevdtb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtjsdrxrix.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gtowpikeyw.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtsjcehmub.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtcvzezkad.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtwnblblmy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtreopiklh.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtyqfhmsbh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtmgmpvfit.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtuojdflch.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwtotkear.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gttqqssnop.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtbcjnmumn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtugwfgijk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtahdrsrad.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtznxmuryu.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgdhjqtai.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtbfqmzxnc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtxuoiqzrj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtzeuzhcft.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjgbuiuim.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtljuvcesu.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtniacadpv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtsfzonpoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gttapxpyfc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtezeumhje.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtftzdvdwj.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gthkjeylaa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmririsfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtqeloxinb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtducznuqg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtyxctklpx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybbobvjv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtpgzazccb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtwaayuuow.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gtvjlzqzgm.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtwsjdczff.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtvgjctlwy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbflraxv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtsnpxelul.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gtwyskwdpj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtsplyyefh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtzrqkdyyj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtfqcquctn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuonsjpkt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtklmklret.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gthvshwubb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnbfvshyn.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtzypqeavx.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtwpsfzgzn.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtilyzxgln.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtwsmkbnul.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtatynmqhs.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtiurrahkr.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtcovtpyph.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtnxfjlhnm.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtuorqjvtx.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtxzngkaqc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtqdxjpfan.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gtmtehqqxb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gthoguqyvs.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtrynvoazz.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gttwwlqwqw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtjdvufgls.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtxiglliwa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtothcwruy.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtnfkuasbf.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtakdrutge.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtpsujawry.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtdzyetimy.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gttrmkyuvm.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtvvzirkrv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtzvriuzzk.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtefssehsv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtxhjugdca.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gthwyhyeib.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtrdjueumh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtibenogut.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtwcwbaqga.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtcwizxzou.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtuygjbofv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtjduorttq.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoeshvfg.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtssbyozdh.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtdhitidqp.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtbdumrmtn.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtnyzmdgww.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtkzpcycan.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gteuainwlr.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gttarfgfie.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gthluupshq.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtbqcgfsow.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqpdkotdl.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtyakkcllx.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtqccjrbmw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtygdoeucm.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtoqksqrvu.html


<!-- 参考信息 -->