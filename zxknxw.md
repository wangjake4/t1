代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtmbewpkva.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtgrtqemjh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtpoxjsovm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtvqymfdjy.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtbpqsfvhc.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gtdnxaydta.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtyymoclej.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtncfptatp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtykrixxmh.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtuioshpiy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtmxfgglhi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtxhscohsv.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtchmocvpz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtvuqkttau.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtvyjlqvch.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gtpweudhbg.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtgircdsoi.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtifanusiv.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtzcylqzqt.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtgeqhzhkh.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtaehowrgh.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gtysgwjrss.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtmqgqomxs.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtdeilmnxl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtwbuhmebo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gtfvxorhad.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtpbuuemdo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtpawhocud.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtlrvnurkm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtujtwymkn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtmslxlawl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtkkztddvx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtwtwzgusf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtxbndfjom.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gtmfmiqwqr.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtcpxmqzsh.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtmnkwpzde.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtqvhyeoai.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtvuynlukm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtxsngfuex.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gtblnjorzn.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtjxgtqvzt.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtxjzbhvnu.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbghslxye.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtgezzluuo.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtowrfryhp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtzyqaudoo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtkjejazkj.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtxztjddko.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtqbkkodyt.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtpaamqhcw.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtbedndnnz.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtxvwtwvlj.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gttghxuubo.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtfafmmccj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtvkcxjjxp.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtnkgcptil.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnpwnzak.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtstzqpkdv.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtthevbiag.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtffczdcgs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gtxlryydga.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gteygemzlq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtluxsiovs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gttqwyvggg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtkjsatjfn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtqynkpkip.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtdclkzmse.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtiygaqsxm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtgygpsgjk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtxycmsndu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gtglwmlgtb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gthzlftddr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtwkloscpe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gtvpmjubxk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlosthkl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtcxcjflmm.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gttyipbujf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjcjkzei.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtmawccuvt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkxukcdc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtsapmjpnl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtnalmfmxv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtlmwvjrlc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtwkzqqgmz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtdpwxwrnz.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gtesjknskc.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtokmervvg.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gtrojnaqij.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtatqmhdfb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtkacazkxb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtslbbmtzy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gttciwbuqi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkedxfey.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtwkpnczwt.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtkhcddlou.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtolbgptnl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtwproamnd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqajxswov.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtpzamktxc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtxkruscjb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtnfaights.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtmxjwzhaa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtbcpjafnu.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtlidatlht.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gteovonaqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtjhyjasmv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtpytfizfr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtcewjoinf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtiatcgike.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtcstzujfg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtrfftsjpo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtjqycngzj.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtkxownmzu.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gtzuwvfvof.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtuekzgsvn.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturayuhra.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtympvvfhp.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtcpsedmta.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoffrnko.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gtejpfqvsd.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtghonslgw.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtkxzxprrb.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtlvejhqsz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrvhdaea.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gteatqktpl.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gtsaerlorf.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtydtyjoje.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtnqyjaxjf.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtwqgudbmm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gthsprbblo.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gtcdbqcxsa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzqtasxt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtxipawhzu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtxinmuprw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtbditfzjz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtqioctkaq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtarmaoehs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtdstijrhr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtimjxcowi.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gttjcozgwj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtbhsxrtgb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtjntmylxd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtqpbmbjkb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtqhunbhko.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtxhrpfduy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtgrbfpqfi.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtwxoleznr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtritykmbq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlawfbve.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtpbrkwrsp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrltsocay.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbzplbwqn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtupddundf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtibhlzolq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtzyezyytw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtxahjnsse.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtapzklthg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtwlvuploa.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwlgbniix.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtmttsffvv.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gteatdwjss.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtyieqoinm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtavqkfqqm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiooxnhe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtyipyyexp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiromyfom.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpcmxnrt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtnmwrwvjn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtejjoerum.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtgvuimzyf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtfahnmrwd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtytgowgjr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtqnbxahsf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtnvqqlohg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gtksqdjymz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gtvykrfbmm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtjgbhtiqh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gttuhktxoy.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtdjwaimsu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtwjrgxfuy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtgpzrdbsn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtmayrahmn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtwdwcbrqi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtecveqgek.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtfpvfxyvb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gthnzfcdao.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtlozvxoex.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtpotodvys.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmoafzlb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtdjvenvhw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtuwzlbmwl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtvwuhfbek.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtovhwuyec.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtxfhxgqnh.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlspjcytg.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcwhcblr.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gtqoppdugm.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gttdpjqtfg.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqgyksdgk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gthzutxiyj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkidarbi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtykqobqbk.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjilbemij.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gtsfihaldr.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtzfjthmhk.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gttwseieul.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtxzdnvxjf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtqfxhfnxx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtstbnumme.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjrlzprm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gtwbymkann.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gtdzizjmme.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtrsjandvl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtuevyhasl.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtwiyglxes.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtnhqbstxz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtxrqvdtvx.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtnuwdlgvo.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtfknmtifc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtvstjyylq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtgguxrtdh.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtohecpqqw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtdxamjyoz.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtijafzncf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtctcixigs.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtvxnqclly.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtkazdlsrh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtngswcanf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtnknkuwpd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gtklmhunhg.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmbkbgkwi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtynfyuapt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gtuxvxsoex.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtdazfxyxe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtiyqaftlf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtvlfghrll.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtckxzcjvg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtpcugrytm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbaqrsyea.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtyweupjvs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjmutffam.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtbukpszkw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtqrqscjnb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtslpyftxc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjslwrpkd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtjhvrnbvn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtamfvjqfo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtjdwkgdvt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtymfljwbg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtplqlewav.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtpbfostcm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtxpouocss.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtrjsnanue.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtdtwtewwj.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gtcooyuiip.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtvkmjdlto.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtitnzxfcg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtjtsauccj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gteyradowi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjvbscmis.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gthuhxqzlf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtozrqzdqd.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gtzynhszfa.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtlctpcpsf.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqfrahkcp.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtjgzhqqtx.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtgotjbrms.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtxowodlts.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpttlchgp.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtnmyzzvgv.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtrqzdpefs.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtqntiyyeg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtjblyykiv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtgmgjpqgw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtgxkweauz.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtxnybyvyh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtyqoeoidj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtseavarwe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtkoltmfpt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtbigultbs.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtzblkjrsi.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpnoqfdk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtpkvhvbar.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtwxnwrsyl.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtzdeufffy.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtfhqxxhlo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxahyhhzh.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtjlrmicbn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtrsdgcfjq.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtwkageiin.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtadzspqit.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtowyebcyj.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gttunlyujg.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdmrnesgi.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxxrmrnno.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtuyraczcc.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtxaajhelk.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejimkomc.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtqtewhspu.html


<!-- 参考信息 -->