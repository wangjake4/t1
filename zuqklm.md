代发 wailian999

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gt2nqrgtxjv.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gt2ucpiutqm.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gt2rxvsjrki.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2gfwdtwmj.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gt2ytprydcl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gt2oghxjexd.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmysxhyn.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2nxvyktkg.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gt2bwyonoeq.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gt2nbkvqonc.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qftevcff.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2gwejxzwr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gt2vehvxlio.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gt2czcdnzeu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwnvzhsl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gt2plhymedw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2yqfegrow.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gt2ttskeazo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urlkijdh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2fufcrklq.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gt2jhtwyrwo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gt2qegqrldm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gt2fxvabhse.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2qwhdlzhn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2liiocwjb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2javngpwd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2huqpdhwx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2fjhllhws.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djsukutr.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2jlqrufew.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gt2scgmnkpi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2cwomcbkh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gt2jywgwsza.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2sxqvhgsq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2zurszdag.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gt2xokhhwui.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gt2oozjmhub.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gt2xuwiiaja.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gt2awhlpqlm.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gt2xgbotqlf.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gt2devynhlr.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2qyhfvkhi.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2emcvbybn.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2trgricmp.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gt2vddeimfs.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2eicnnqab.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2dwhigltu.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gt2tqtuzand.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2izhwvstd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2orkjmnyh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2uhtouijb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2cqrzjpwy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gt2fbujeybb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gt2dlzdvxwo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gt2zgwulgwy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2yjiwdhmw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gt2ivgpqxke.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2xxsyxwiy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2pzdqhhnp.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2haxkpsrt.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypgycbui.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lawjidfl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2mddaxbfw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2wtkgwdiv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2czfggbwr.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gt2qjezkpkn.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2tvmlvcob.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2rmpudcyk.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2adtxjqrs.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2nqnecmog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2pfkligdb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gt2cbtkzdno.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2osvbwwil.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2bqjstctm.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2cltrkhyt.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gt2tovypekv.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gt2aafqujso.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2qlbwcfhn.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2lvxixhpg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2cmylmgof.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gt2qvmbxgot.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcxmnzns.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gt2enrmcsoe.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gt2qzmkjovz.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gt2lwbpidja.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gt2jauvchxf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2fsqlwyby.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2wthkryhn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2grxoigvb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gt2ciscdedv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2cterkwwm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2jimtzdhh.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gt2ryohnnru.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gt2axmuwmij.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2ujulvjyq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gt2ydwyeifo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ncynwxah.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2hwgxqptw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2togaddgg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gt2dbivbdoq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2zhrxawqw.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gt2uprnpgyh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gt2pxftjxwo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btmwlovq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2dnxbckmp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2edmzkily.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjugqgtf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gt2xvozocfc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhcqwkvq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gt2gfcuaflw.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gt2nsfwiegs.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gt2onvkfltu.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gt2bnwvntcu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2blhcnive.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2gmqvrtav.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gt2kxgoztqt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gt2efyagcjk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klxfwytp.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gt2cvwbsjgy.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gt2sxazgruc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2oefplghg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gt2qsormowo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwcrgegb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2xycgxcmj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gt2kdezgbhz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wghcpcds.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekdrnrdu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gt2twbwsjjr.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gt2ezmfoovi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gt2mrayxlcp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2zcckpjmz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2ygqtaztv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2mwzzedec.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2ufraatgu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2vrueovak.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gt2rtayhixv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gt2rwfopsvl.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gt2riuemsgu.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2qtbrcwsq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2yfsiiygb.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2epojatpm.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2nxlfasvu.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwjqkrga.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gt2dymotdgn.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmnlonsg.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gt2puguvkyu.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gt2cvgsdxko.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gt2sccymjwv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2suslnjan.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jizvxvrb.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hkdokeeo.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2cshcakul.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gt2ooayvwum.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gt2cndlskmy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2iqjcitlm.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gt2mmikqfph.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gt2fxgnxred.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2wzfjpotc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2xkjyfjfr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2rgcmywlu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2fcqcvdjd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gt2bwidqewo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2cwycqksu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2otgubmjy.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gt2pkguzods.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wenqirbu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2celgeeni.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2ycgebjuf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2eymcujzj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2xqfghiyu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gt2rgnbrnmi.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2oexumzvs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gt2ozjyrbvv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2phdjxmbp.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gt2rhpqnkzl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mnnuekxf.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gt2tvawelcc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gt2blxkfoqi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2mytiskyt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gt2nezcyvjo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2nvuyhftz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2aapcdsjw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gt2dogqwtgf.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2uihoohsy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2jikcukwb.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gt2ikahvzkc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gt2fmsghlpb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2mcstzzhd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejkpxktc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2rpczfnbc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2ogxyvxba.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpjvwlqu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxxevziz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vtutvuqi.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkqzsgeq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gt2whpimlss.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2owhopwbp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2ajrlhqiu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2fzkyricu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2dpauquaz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gt2qfquuvsi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gt2lsvlwqff.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyhchgib.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gt2judfhxdt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sudljryr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2hrpoqwen.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2egtskips.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2cfyzgwop.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gt2xwtdhcqz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2vskorkrj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjnxcqyq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2clcssyjj.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gt2czusfzqp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gt2xwpzdjcx.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2srtjljxg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ufpzywey.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bidzzmxz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2jgwnvgwh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gt2jmhbzlll.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhhnrdqv.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2hcknzigg.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gt2etusycof.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2bjdmysfz.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2unoszzym.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qnjlkaml.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2datbzcdp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2syszrpsw.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2boxoygiq.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2kviharjw.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2jjnbsbhu.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gt2ekorohbh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2sgxebtau.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gt2ugahxlyj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2omgljclh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2vlmyeekn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gt2npcnfhul.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gt2hljqyvmq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gt2fdpssgli.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cucudq.cn/Article/details/gt2qmfojiwi.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gt2royxbdkj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2hyzfnuwj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wfrieemp.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2isehqujq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2wyqfuwhi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2qgmrusis.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2niefdnoh.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2uhhgiilp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2ngkpnamz.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlerpuch.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2klwaqlas.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fecryqws.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2jywefgwb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2frwhmzfl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2wiwxvcjd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gt2rplqubbh.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2kijrafpm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2ziuupiza.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gt2dqvxsipd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2tdhcdqes.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2kmdeknjm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jninppto.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2taupxvfu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gt2qyoiqvvd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2hnxmssxi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2nylhokfg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2gbyaobzk.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gt2ctiospou.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2yihrouwr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2niigdrmc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2yryjyzrx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2kiolwsje.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2oqhacoua.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gt2nqswfwrm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbyatewj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2gpclxhoh.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2uqczkjmq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gt2inmeddyv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gt2tphglltn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2lbkkazft.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2driswjcm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbinjeyl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gt2ukadbwbg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gt2vmvsyium.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gt2zbwnnbnt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tlvpuikr.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2myzftftm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mcxdwvih.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2jdisjyhk.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gt2onktihlv.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2fiuogpmq.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2iruerwcu.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gt2yktnubxq.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2jxjmbcsk.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gt2opyqyavk.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2jruwgwyt.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2xtxfedla.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2vkpmfsje.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2ufzjvvuh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gt2ezqvddud.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2nxrhgfmi.html


<!-- 参考信息 -->