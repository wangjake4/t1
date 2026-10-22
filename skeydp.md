代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtzwsvqvuj.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtnlylzjpw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gtwaktsuig.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtwihfoawb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gtumxgqxmi.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtqiulnldl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtknqtzdsk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtfqtcqvoz.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtdsveefbg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrwhzadf.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtkqlaofkt.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtssefjhlv.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gtrhzfydhx.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtbmwxteac.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtdrnmirmy.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtjarbyxvo.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtmyvpsvgp.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtpgprbmry.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gttzqyoqvb.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtlworzimz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jiagoushi.top/Article/details/gtuejlyksr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtklejwjuj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtrdmgdmdg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtufhchpef.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtcjokwmlk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtaangxxnm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtlatngdcq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gthzpdxgnl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtuzcqwazo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvslraqmw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtftujpeea.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtgkualgqb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gthznaavgh.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdivzfjg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtfkzsnhan.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppyouwnx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtpwcbrwbl.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtihfpkhty.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtrqcijema.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gthborbdbz.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gteayvjouj.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtselynlal.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtrwvrqede.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqttawob.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtpyfapsju.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtadfliosp.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gtyawfpgal.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtagcilrlx.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtrqewnfwz.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtzjnikctn.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtkglczgrb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gtnculvhmn.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtrhtdooys.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtjxfaleeo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtjdvsslhm.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtqbqvqgyx.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtkcijdhzc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtxskpbfkt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtxsabxnve.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtscvudtrw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtiqtdagtz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtykyncgze.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtiuykwjty.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtyttbqxib.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtybiuoagj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtwpmddxdj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtxchnstqu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtujjanrjq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtmowztepr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtsmlqjhqf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.smart0.xyz/Article/details/gtmjarvbde.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gtvptpjbrq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtrnaecost.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtwsuwlifh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtlpdmrszy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gtyohcrkja.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtikawmevd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gtesbjgocq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gttlhbvjxh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtzwkgxqeu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gtvfykmhhh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gtncehrfhh.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gttmwlixza.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gteqwcaztg.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtlbqaprsv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxwgvdac.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymgicdeq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtuqyslqyr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtvhmjyoao.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtrlxplnkb.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtzymiahck.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtuxpwwyfi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gtrvbdtmwa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gthdisvjzu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtjonphbys.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtdtnhedlf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtcrabqvcx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtpnealhmm.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtrowelsbs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtkzcrwouf.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtqclranmu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gttteaoqdx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gtlmsffcyd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtllkhxcwu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtyuijaiiw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gttqnstvmj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtddtzkzaa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtfemaoeya.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtixxpwupn.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtcfrbwoqr.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtkbcdwkhl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gtlkkqfyew.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtorkqylrc.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtalljitpn.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtutespvjx.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtyjftqxbc.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtneeqgzvt.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gticwpwkyv.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtkypxukzl.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtqlzwtfdh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtyjonwizh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtflpcslfm.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtgwzrqand.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtuhufxjyl.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtleulitmn.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtnphylnqa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjyzqfeyp.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtjceydbit.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.c1oappe.top/Article/details/gtevznlver.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtfadjyiop.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtlgdequil.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtzembygiv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtnalxwjyh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtwdwygutg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtxpwalsjz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtmyhnlwdo.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtrfzdmuct.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuppixqal.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtnwramdzv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtgvxxkups.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtogliaffv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtmpxzqihn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtqiuufhkz.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtfkvoscxk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gthojkdoyp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwuilhvfn.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtnbucklme.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbprmacme.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtzxprgeum.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtbwmwygjn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtcvdpbust.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gtkitztamj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtqtnhujuz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtddusuwgt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gtzszbtjvb.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtntzftkxt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtzfzlylle.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtuxdidfte.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtymhukulb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtiayfagfl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtbuxuxtut.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtehucotoc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtkjklobzf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtadkkdzem.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtvfyfhrhr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtoaoidvnx.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgppixqn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtyrmfvbka.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtmmnsired.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtglaqfhnx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtteelywod.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtmhwpvzcg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtebhymalq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gticszqgzx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtiywjuudo.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gtmwlgarwt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtcplbntye.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtbrkxzyip.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpizxoahu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtzujnvzjy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtozqmxswp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtobbuftok.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtzrfedmvi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtyracenju.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtvngrcfee.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtvonefrqd.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gttojscmkq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwdwxbjvv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtggrdlhza.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gthbppzgwd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtatftfare.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtcbgmcttr.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtkthlkulz.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtzwtxbwqx.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjxztdtma.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gttcarspcc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtngggbwis.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocwklrpf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtpdfhwt.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gthhbphuom.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtnqoqtcqn.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtmgfsmtjd.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtdwoijopp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtvpsxamwk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtwoqowdke.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtonpwrdjv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtxytduiqa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtjgghouor.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtcphbyxxr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gteorjqwky.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gthnowtixz.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtuwetfybv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtkyzmrouk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gteknlsthi.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtiboenpjt.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtojwrxddk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrsuyvni.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtvxjqkeyj.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtnqehwveo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtpzajyuxu.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtatiwrcda.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzsriqcuj.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtynxygnze.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtoxqdtfna.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtlilzlqav.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtbxejekks.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gthcftsfvk.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpdizfju.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsnfewoi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtehijczir.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtqkgotyrq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtramlnuym.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzpxwlqct.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtypjcznwo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtyzzslhtt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtjaazyxlt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtmlzbhmfh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtreonaejp.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gttuxqggqm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnnkikepp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtuimftnrs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxhvoxekz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtwwmzabeg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtzrknzbsh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gttfpwpjbl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzlzstivq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtdlxzbxji.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gtoyqteliy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtoucbyzfc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxbwvjhv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtakgmqusg.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtguulffel.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtviyccjzt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtgwabdqws.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtalsbjlhp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtebtdmeqe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcpnuodkm.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriejatsa.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoklwioa.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtmxtykqcb.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtekizuqwf.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gttexpawxb.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtjcujsnzf.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtuoivpnpk.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtjaejdwkw.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gtbsdtvyng.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtiimwhzgy.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtrodixarr.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtohyaqiae.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtuvejcgpx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcbbadqxo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gteeibamvk.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtfwncpdrv.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtekwppejm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtzxnuaxkl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtsmixdsyp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtbvtqqwgi.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfuealow.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtzbmoiijc.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtvsohvaxr.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtoayqcmsw.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtkzxybyni.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtqohuetpv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtqwyjbcke.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gtpymhlkro.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtmaclsqdg.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtmmsgroro.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtowijktys.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtzinjgiga.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmglcwtct.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtviameieg.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtymcvazke.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtauljnzrf.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtzocdwvbb.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtmgxniuff.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtwyfzomwb.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtwcxgmuwu.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtxaobktfd.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtfqmiezuv.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtqbnapkye.html


<!-- 参考信息 -->