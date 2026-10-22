代发 wailian999

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfffmfzv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gt2ncwlcfhs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gt2cjvjwtfk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2fvyfbwov.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2xxjgfeiq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2kypylbzq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2ohqxnmgi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2chnvjdli.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2bihsuhno.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gt2gxtmewzj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gt2kascjjjd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2oxroizjh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2sutymzsa.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrwlqdyk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gt2xlwtohsa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ejlepbzd.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gt2oduetpmu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gt2sjhgflpt.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gt2fwjmpnwv.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcharaxm.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gt2nqsuqdlg.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2yaywvgul.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2vwhlrzln.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2ksbucbcc.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gt2sbegnwcc.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2aouyhsjx.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2jskmjfjt.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpbqqcss.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gt2lvjljjea.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gt2ugwfwzuw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2jnvcithd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2lfyyeljt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2sjjzfxzq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gt2knieochb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gt2qyoxlkzv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gt2gipjpvmg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwoltlrj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2aywbctfa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gt2ezxckyae.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqkqqlmo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2shqvmahs.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2hetkozks.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2rtdelilk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2mkmhqfrw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2yungxkto.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2ijayfdmt.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhtxgoqt.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2lmdhluua.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2bviylhxf.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2qaqkrzih.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2xxxhkuka.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2dzqmggbl.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2lxmypjzd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2lobmesfw.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gt2aftibvfq.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2pkpwdaeo.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2ylvhjqrq.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2zolmhghi.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2bnghwzif.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gt2xntpdakv.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gt2pmsqmfkx.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2mtgwvzlb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gt2mvdbhjxo.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gt2qgkvdgyl.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfvwdtci.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gt2xuouyqsr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tyrgjdbm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2cqkocunz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2zcdsdwgj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2zwmazgwg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2xqsgpfuq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2agccbybv.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gt2deazdlwa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlcsciam.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2xyccbyko.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcsjirhh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gt2epruqwlp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2hjsrdaco.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2uukuhhuv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gt2xsyjkafs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2tpvvoujq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2rqzgntnc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gt2niudirdv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2fhrabedx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryitrdbq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gt2gwgzpwml.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gt2ritfhfso.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2mfhoqxxy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2rjzjubdi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gt2mqknfgiz.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvcstwja.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gt2krhniwfn.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2oyyzoind.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2fkaosvpk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2hxswhysk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2jroeciui.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gt2djdodnfw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2kavzmjtc.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2osibydux.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2eemiehpy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2xlsphgsi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gt2izybzgev.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftxegdmk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yikbutnl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2abdtnrbx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2ziepnpjb.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gt2lptcfqrw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gt2hdashklx.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gt2dfqeczdu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gt2fxtvwoku.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gt2sxulzirt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2gnuuulec.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2aulbfnkb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2dhxrdvcf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2samtjmob.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2ydrkspos.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gt2dzjiqbri.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gt2ukbaewmi.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gt2aazbdrel.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2aftotrtk.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2wxmewasx.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2iqmepxud.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2aczkytez.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2ycxmhsof.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gt2zlpkokit.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsqcwypf.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gt2mwohudrg.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gt2ayxrgboj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2uqaszvmw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qhurrkfo.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2hermkuor.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2nowktrwo.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gt2gwnzupjo.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2rgxfaeiv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gt2uqrlalpi.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gt2jnaqchci.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2ksdxuxyc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2cmlainen.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkvamxe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2wpvjjgna.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2lighaqqk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gt2otrayzhh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2zcdzqxzw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2nyipovfs.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gt2xxvwnfah.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsgeszge.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2pmxuvssg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2qobyqdtk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2cuyxyglq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gt2tydpszwf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gt2hvewvmmz.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2ozatjslt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2ngttkwit.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrlrzzyz.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gt2jebjckhi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qgsncmxv.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2dcdfgkin.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gt2pzrttbhd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2fwqdhwsl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvgdvxoc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2uvagtcgr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pochfajo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gt2redakwjm.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2yuatxnxv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyrrcmjv.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gt2mnlnpevk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gt2sxoghykh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vgjjaiys.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpdcntmb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2zrbekdcw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gt2dvqipzbh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gt2ialbahyl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gt2lilcnplf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gt2hgwwzmln.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2vaiovfhv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gt2vljfloix.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2quxxhaef.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2joumxziq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2ggwemxkf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2xyhvcihn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gt2hxeobutd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2zcwuxfgk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2hxymouto.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gt2antheozh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2suwwtrfy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghxaeqzy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2neisqtmi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2htxevxus.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwgnmfog.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2gyndiaan.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gt2ahmkpenw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2csqhpwsz.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gt2neeowmnu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gt2vjdrqekp.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2krsiumhj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ojzmepqk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2exrxyldf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2hxminfgt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dprcwrrg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anorpxci.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2gobjibev.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gt2rtdtllua.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2dmgsmbhi.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2jyhzzhvh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2cxsvebka.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2lpyxmvlf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2kmojvsry.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2qukrskny.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2otorapew.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2zsocjsbm.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2dmioifgu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2rrkuypax.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gt2nyowiexk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2lmmqjodz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2rjtoeiqy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2ytbmuzbi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gt2cplzngft.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2wlujgtot.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypzfsxib.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gt2aulqodqo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gt2qssgyvnr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2pixfnmtj.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2rohfyjjw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2jggmnnlu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2nwxktnia.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gt2pfhndikq.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2cwzmjido.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqxnqikj.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gt2pkcswvdn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2lrmvwreg.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2kfqbeyar.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2eoacpyzj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2vlynvjnn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2eltrtbmm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gt2bvdkwylp.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ixnpscqw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2blqdqgke.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gt2zbuxxkki.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2fingmosr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gt2gfwdrrgf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2royiauty.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2siuilrsb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gt2ulahcilw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxtdezts.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcprqhbl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2fpkrsmvy.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gt2mwuoddep.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkxwtjxv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gt2mcthfllq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2mjvhtwte.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2pnkwmsqz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2jwosqwfm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apsmzdzp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2uaorcqhn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2ytwcxnqd.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gt2lkwjpmyf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gt2irhimkzc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpnkoalw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnimuhvy.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gt2wtvacdsp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2kxisbonw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gt2subwlinj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gt2qznhpmbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2vgnevhhy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2gwguajsh.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2pibkyqji.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rmzrojdw.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gt2dtwjhwni.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gt2wtcxrjhg.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2oglumxom.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2ompaxxdl.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gt2cpimsqea.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2lryrigzt.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gt2aqrtupur.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2toqsrosp.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ghhhamea.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsrqjzpp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gt2nyhkkexo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gt2kstjyszf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pcxyzjqf.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2izjdlart.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2ufzprull.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2tcumkiob.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gt2hrvqwglv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfjsadak.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2fuaresgl.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2uxjmuedj.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2liijhqqu.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2tdwdsyjg.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2uoazqvhx.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2hctexywa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gt2stejmuor.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2noaxyssp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gt2siiubvka.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2suddhswa.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2mtzcypll.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2muzxxlfx.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2mnlrdexg.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2jhivfkko.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2fgekcvxv.html


<!-- 参考信息 -->