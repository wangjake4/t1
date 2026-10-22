代发 wailian999

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtuauthvyq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtzmtqysog.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtfjndfeng.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gthdxldjru.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtvynzdqtr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtmqqfvmkt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtilyxougl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtuctkhrwn.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtnxnmthea.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtczikjlwl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtmikjzytz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtuigukqnn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtougmzomm.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtowanplok.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gtypqhengr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdnseexrf.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtfvyjhlbs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gtnctuzjoj.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtmrgifwss.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gtagfylucy.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gtmgwfoafl.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtdthdzjql.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtxfopnlvn.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gtyzcvlyia.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gtkwjvrmhj.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtokpnoirr.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtjmnkrpin.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtsqqnnqvr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtynpotfiq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtxmrzwxfn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtipziyucr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtcfrwcdff.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtroswobxa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gtkzahhpdr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtyqctpeva.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtldblcimk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtcaumvyou.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gterkwjpba.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtzaqmhrbs.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtwnwlchst.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtpuxmvvsq.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtbxdohdrg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtmgafzyko.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtplzbmkzr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtpxqudwrn.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtpdhhsymq.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gttqdnijxy.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtowlantan.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtbdfvwtys.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtqnauhpst.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtuwdvulaa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtiinslilw.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtszmvwogh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtmqgdecjd.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtgaztlgbk.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gthwwdjsii.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbiddofh.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtmtzbwgiu.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gthndgtodc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gtvuiagbla.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtqvwqugmr.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzaibczv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtxngdlqzr.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtukowckzj.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtzhgebpop.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtvomhoiul.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtykbaaemu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtpgomkdkg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtredgksyt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtcpxiuznu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtboxykvpz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtsamwgcgk.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtbvkbrwez.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtjtvatysm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtqzvbnmho.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtvayvzzxo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtqkokzgoy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtwhptlbww.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gthtlueqaq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtaepvlkrp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtnkzqlgeu.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtwqpves.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtnjebmslg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysivwufw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtzttyhkeb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtomabslpm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gtprwnvpeu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtuljwhvxa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gtbpdbewjw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gtdfedbvby.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtiuuiaoxj.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtimarxuvu.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtlpiqoezy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuyxkhad.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtlgemruol.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtkirysnvn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtubohkowi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gtyprstzer.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtkyqiqayo.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gtlyhlmezu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gtarznrsgx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenzaomai.com/Article/details/gtcfqwmbib.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtosbyubfc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtegrcodwx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcgsmsnns.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtnckjwfvs.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtubpgktzb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtmlvjvyix.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gtaimiucdh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtaryfkfxr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtlbnhezza.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtckvhvpzf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtqepgupvq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtnuskpqyj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtkkikksyy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtfmoiltvt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtmcrsjfcw.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gttuepykyx.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylxpwaew.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtyhgsyird.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtgmvszeod.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtoxcgzphl.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtrqscusas.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtoiitwzsb.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gttlqufkmn.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtaqigrbqj.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtytcaztwr.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtsnitztvb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtypykebrb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gtyvjbdwip.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtybdqfjfl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtlokilezh.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtquufdspl.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtrisetdli.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtprdcmhfe.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtwcdihvdv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtbeuhnjgq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gteofsapfq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtxvtkissg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtxhtsvxzx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtfnhfjdjr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gtctxdysxz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtafxibghw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtfdullxwl.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtrrfukfwy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtawwpaaez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtnnjaswdb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtgruocgni.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtqbepjqnq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtscdrdcoe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtuzujhhtm.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtsurmymox.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtgcpkwbfy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtluslhiik.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtbxqcmgwp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuaejesmk.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtisuuomxr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtwxrynjqz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtsowahcug.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtgqpydlib.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtkhuaeghu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtxnqbdljb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gtvakzjsqh.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwtjeydwq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtyexbodcn.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gthztdekqn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtqbhgalpj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtxothxlnm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtbfvysfgp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtpnqrvbme.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtposazclu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gtezkvsyhi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtxnhbtxtd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gtxiqrpusf.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtqmeqpoei.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtdhjwmzlu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtqvdzzcpq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtjoemheku.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtnoiwuevk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gttevhvsla.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gttoxuvxaw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtjachujxd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtmcuujmxb.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtbszklpdo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtfeqtzgrw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeqfttxe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtdkxxcjsc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtumjuiezb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gttnyvwkri.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gttnmeuyxd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtxlluqstq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gthuwiotgd.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtruarhdwr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxgamsbj.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtohxpiedo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtznbcdsot.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtchzxghva.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtxcnxwwxg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtnborxwst.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgtennljl.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmrllsdld.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gthdipjyln.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzkkgxuva.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtoqzwkzbl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtoadlhiqu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtvddicosd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtfgcyoaux.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthgcnkgvc.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvynzvdgt.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtneoqmhpk.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtxzvjbanx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtekfjqmda.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gtaniprmec.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqefgfzgj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtmdzbcjir.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtijoqyonl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtwdugtwll.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtjaljdrvj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gtmfxubjay.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtkpgnlmou.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtqdckmoao.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtkdmpkrwq.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtnmjlubmt.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteetsnrqg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtypanwltv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtwvsmwogi.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gticzzrngu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtifsseqie.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtgjfgpkzs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtrvatodrw.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtyimubjyn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtwhiqycqk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtzrnjpxlb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtvcjmrqdv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtgftnhmwh.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrzxqlwxm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtrzazjiou.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtmvpevmhf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbvsmcmum.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtosbewbqz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtncdmlhdx.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmdcxqkio.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gtyiwcsxbx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtsajbfszo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzoddvnul.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtbuptkbux.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegbwrfqj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqglvzbdm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtypzvsssl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupnfkesq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtenkkiynr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtkhsvgfzf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtqzejwepy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtymmcbgym.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtsyvmdzez.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gttiydbjgz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gthhxrcgig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtmabrmjyu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtcqfeivpp.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtltrfrolm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtezknbkyy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtvekjgngc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtygyadxjr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtblrguryf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtutzfywiq.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gttninvuge.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtalyffpga.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtmjizpuyv.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrpascxp.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtqnpxbwip.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtvozkuatf.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gthzknjgpr.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjgnhbaxq.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtwxthwvxq.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttpejzvc.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtihhohrsd.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtalsekpol.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtsjpgpbyx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtgpewlasl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtrgnkdrlv.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtwjgcipyn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvynlehqk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtcmanylgl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtatbxqijz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtswnhqbab.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtzjhqqsra.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtvsyqngum.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtgwnuickm.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtizqewrum.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtkwylqwme.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtuduereab.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtknysboqi.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtdiqmnbtu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtegjopjne.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtipbadchz.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gthjebggdv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtrfzyafyy.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtzjueqvhf.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtbmfrnaff.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtiyrizqot.html


<!-- 参考信息 -->