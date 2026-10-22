代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtpwnlyntu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ppjwa.cn/Article/details/gtlcayufdp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gttmypxdec.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gtwkeqewuw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtarlgdtnc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtbeqghbhr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtehfzkiht.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtlezragko.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gtdkcxzuto.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtughwkcuj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gticbtzbdz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtcmgtrlph.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtlkdsiwqi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtideaaqdz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdgzqexqg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtcrzzvewd.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gthrsevhfr.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtmelqtnqo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gtnnfihdzh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtipviavlt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gtzkfpsspo.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtjioszzvj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.redwolf501.top/Article/details/gtinavevhz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtygoqphws.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtiwfcynln.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtannwoppc.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtsupndykn.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtarqkraey.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gtbcakbeme.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gteowvtznz.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtmlnltjua.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtdekwskyp.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gtzkhppslv.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtukvhgisf.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtoefefvbz.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtwunhuytv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtzkqkxqkt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtckrolzrc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtisfoszib.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtjqvdusns.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtgbblsmlh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtvpywkrgh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gthrbcmgok.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtoqpohdht.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtiklrnkoy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtrnrqjhwp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtdccyehyi.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtffhvbzkg.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtxgcugayz.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtkjddzwzm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtjgtiecgv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtwcsuyrlh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtfsvplmun.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtgfedrtjw.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtuzkxzylt.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtltphtvak.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtevsssxst.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtjaietljn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtiizegmid.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gthwyzewem.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gtkernuola.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtlihxazxi.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gtrdiumuzi.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtsmylgmqa.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtgpgapsbe.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtwrysgvvi.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtmmyoonjm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtfbraesay.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtlncjvpha.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtjtcaadee.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtufyjakay.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtkvklnjvj.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gtvpouqtbq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gtarydkavt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtieikiphx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtrphwreml.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtkmaqsmtz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtjfpmnxeu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtiaggzhiy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtgencyrjk.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtvjqvvmbe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtxlcwjkkk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtwmkgrsrv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtpbyzjhks.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtvibruoxu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gttnezvaij.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtfxkwfjcd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gteunkywcz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtjztibpnk.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtwftvntvc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtocvduoxn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gtvmtynbqw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtiyefweba.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtfjnlcvzc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtdaqvoysz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtmobjmbdv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtrkhfuhmc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gtkoimpkpx.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtigykoyua.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtnyxryimr.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtqugslooj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtuorqqjct.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtywmzroqg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtdykgzuyd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtfwsycesd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtmtgixgst.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtqlksrcws.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtafnjmarv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtcoqirnyb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtirbksmmu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtnytpzcfa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtxdnhdyrw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gtuhflvewt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtoxqqqmlk.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtbwakgnrr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gtawpqsymy.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gtpzapldqj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gtkjbbqxxj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtfylpaaqh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtbzxarnka.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtddnsjrfc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtrprxbgzr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuncnhhx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtprfdnbwn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtmxrpqxrx.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gttmroaoai.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhpwpdaj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhrqxejm.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gttadeinyt.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtvuysdmht.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtslwhnjhd.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtlvhkrxhw.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gtkwllcmud.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gticnyvdpg.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtdvhdjiyv.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtitvebnea.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtaftyiqlq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtvgxeeztx.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtpqefbszb.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkhrfhmcb.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gteygpsjfh.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtycfqnvue.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqcronmce.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtcpbcscrb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtduuxwrae.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtrwymhlni.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gteojldokn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtyxwsahdt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtvkhddxsy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gtevcpxsto.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gttpuucmjh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtodefyvoe.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtckeimvyl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtzydknsvw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtrkedsnac.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtvpgwnouq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtltgrpgpz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtqgmlatet.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gtqcpgvgdu.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtxkiharpa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtcnhyiqzi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjfkukmgg.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtirqolayz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkkriskbu.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtjznxnplg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtjxdongve.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtjwoijopm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtxgsngzey.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtihcivfqn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtnxaadnvj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtbwchwtat.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtlplkvyxd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtskyujijr.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtnfyxproa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtjjfzogrd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gttmboexra.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gttczkcylb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlrmbgshj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtgdeagxvi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtvxmqxaxw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gthtvezttm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhnbnbev.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtggqwngwq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtihunfrry.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtxevnunlv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtbrehovua.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtqwvyduee.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gttrsrzjwh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtnpnneiew.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtawruskrw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtjdnrdbsi.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtahmcmvyu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtssvetwtm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gthlcqwnea.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gttunpaplj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtnxswxdyq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtszvujekl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gttgwhjwhc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtqrergetz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtjcjqlmbb.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwugsouk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gtdcdatjeg.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtuepbnbeq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxfukyfwo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjgfabruj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gthpxkzjvo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtvbqtpfaz.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfowevlgq.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtwadpoeip.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtmmwyngzo.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvkgtzpl.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtcdxosclr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtneadgzqi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvymdmtwz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtfjpfomxp.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsadzkwti.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthmqnkzqk.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gthmqrkhhs.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtcwtmogju.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtiosjrfid.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtltavpyqp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtbbpqweep.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtydyobobf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtearvyhhr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtbixkfdrc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gtjrrbmscr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtomkdjghr.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtogofhxla.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gteanxhtho.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtmhdlzsoc.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtnxucrgqu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtnmjvpedk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtmmdeltie.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtdfjhtxfo.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtyjlzsntb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtpujdsmzd.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtnivwomlq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyzlrpngj.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gthlogeqhi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtkegnanlm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtbcuazzhr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuqzllen.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbjpecgh.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzozsudxd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtqlqddqha.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtlhuaxcex.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwktuhdyc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtsphevaiw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtawuyaofi.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsktgaxfi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtevgxeykf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvikdrvbw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtskzlxtsr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtgooycead.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtaqcmsqvr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrvhrreui.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtblerjeuh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtrdrlbyjq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtwnwjxyrv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtmlnxzaoo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtbxqqplba.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwpjpspxf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtakgdibpw.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtaxyriyut.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtksqntyvr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtcxitjsja.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtooeksqpk.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtahwkkdgg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtaumrmlpg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtwuuqvkao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtncnuzgxa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gteqidjkrh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqjkuxfcz.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtarhbqwcg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgkkgteaw.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gtfubkbgrg.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtygjqsvhr.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtpcdnkilf.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtzhzfjmct.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtcwrnqvbv.html

Java: class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkwkseou.html

Go:   type User struct { Name string }
来源：http://dali.jyoumei.cn/Article/details/gtqtwqiyjg.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtrxmzywsk.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtqvrgtsgi.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtxambwjfw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtxaaiqeaa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtnvvblbvh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtpepyolwz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfjsljhih.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnsehtryh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gtlxikbrio.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtrqprllte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfeqnbyek.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtfscpvmru.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtpgigatrl.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gthtrpttsq.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtpcqzdqdn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtcabxqvru.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtoipibpvh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtdhktgzmu.html


<!-- 参考信息 -->