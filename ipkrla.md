代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gt2whaxrhxi.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gt2wtyfstdx.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2payxpzdw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2bnocicgu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gt2gzgvgjzn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2fspdzrsh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2thvaxzdd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbbllfwo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2jpymybil.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gt2dpobanmh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2hzwmvydj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqxbxejy.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2nafhndru.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2qpirqsjm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2ejquzflc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2oxilkdfr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2oxsbdgnk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2ezoipqnl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2tyuhaeto.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2nvjcuaxj.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2wehkykdi.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqkskdxf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gt2rafbtiqp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2fudfamlc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2hsjatcks.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btogwjcr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gt2fxlbrejt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gt2fmrzkoyi.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gt2oqggicbp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gufaxibg.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2lqnlunky.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gt2fjfnagpo.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gt2pmhwzlih.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2wwgbngpe.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scgqcykr.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2ujxucuqh.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gt2oncjyqoa.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2ailyssyt.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gt2wcwlslmu.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gt2ndcnkthp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgzaumjs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2ajalcfdz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2shccuvdk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2nlsjwitj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2tyrercmc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gt2xgakwsjk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gt2bvsoelka.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2vnjqndwi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gt2lzeqcnrm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2oiglxhby.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gt2ncxhoptu.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2swgtyqrf.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2hgosbscr.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2nikdyyao.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2kixmzfyh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yevpsikb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gt2hlinfhop.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2nflbzoja.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2mugszljx.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjqbeinz.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2qwjouopw.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2fffgffdj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2icwfarrq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2hzmumifl.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2jesgbhuw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gt2cifuoqok.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gt2pvnkiexm.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2cmzhanmc.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gt2mlffpbwz.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2crckisxr.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gt2hprhkmkf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gt2jakpexad.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gt2pvttbqdk.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2klhssgsu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gt2dqttcitk.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2zvhrjbnx.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gt2wdgpupvi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gt2khyhnyay.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2cberjjcu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2zxsawgpl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2nrzsmjra.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gt2pmpuhxez.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gt2xmejldjq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2nvejogrd.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gt2djactoqy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gt2nmrhuyla.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhmdmuuo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gt2rvpprifj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtouwnwz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2tskyvrqm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gt2kdifplaa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2aurdmesw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2hnrpoeex.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gt2stxqtgsv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ynkzztlr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ktsdrazc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gt2eybvdzme.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gt2vbloifqq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxjhhzmf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2adkdrkmz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gt2mderjqqq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gt2mlucmuqp.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gt2zbtfdmgj.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gt2gntmxjbw.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gt2vopxwlyt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2ajchsale.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gt2upakeoau.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fypofcjd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gt2xsrzdbbl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gt2fzeidugb.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yicgljgs.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gt2mseobqeu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gt2cibcsvkh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2eooxeoma.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyhxelne.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2mlsmftdl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2wdpyqwjk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2toshcpdw.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gt2ifmmysjy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2xturxzwm.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2djbprhhp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aspwtpgl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gt2hatcqlot.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2hwevwgsg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2fjfdbugc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2afopbbfk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2bjaeueoa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gt2dwhvgmxo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gt2pscrhqnt.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gt2oddilfrn.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gt2vsghbjab.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2bxejzujc.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gt2ismxaqte.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2yketqkcu.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gt2qgwurbia.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2wyupgsxd.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gt2hcpdytzf.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gt2dhdikfew.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gt2eosjptro.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gt2suwkntis.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gt2epnikwzq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xeqwjooi.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uidhgjsv.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2cxagmadl.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gt2tblehevx.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2uvwscryg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gt2dxvfgpmp.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2zbaddemi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aggierfb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2fznoxxbv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2lfbaaqbs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2kawstypz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2prrnxxkp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2bohafhvz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2yqrintbl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2yoxhsdja.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2wvuntozr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gt2kqqhmqog.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2xxktqcta.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2gxlapivh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2behelpia.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2pxacxpav.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgjlfkol.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2rkvptxej.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gt2ikfsdvdp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hzqnpksw.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gt2lvrieati.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2avdzvxmn.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2eenelzgh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2itwicqih.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2esmfddjq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojrqiqwv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dttacdvg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2jvwcropx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gt2clnexdvd.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2obtvbsrd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2gskssltz.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gt2yolvslhh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gt2tzqjilja.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gt2pizpmyyc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2oixigoyw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2lsfzzxpb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2tdeeyjkf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gt2eglmfwbr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gt2veruvjbt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfwdxleg.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gt2bzdpnhgp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gt2jutebrie.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2hrzmxkif.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2yigeretb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2acqbixrl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gt2miipelcu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gt2uxfqbxkn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2qexryppg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2lkgssdpr.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gt2rlbgvglu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2zmrbbksz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gt2ngbqonpn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2hseydpfm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2ruldnxsc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gt2trgmsvng.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2hqemrpaz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2argtqtqx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2huopcrbo.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2wqxxtmxo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gt2xcvftuqj.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2dxgzemud.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2grtdgkot.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2fygxdolb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2xcnlcvrb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvppplft.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2wjnvbftm.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2zkchlfme.html

[F06] 删除文件
来源：http://dali.vqdsnc.cn/Article/details/gt2woeakwny.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ejjmtvdw.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2ascnuftp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2bymegohf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2tfqrmdul.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2hzxufdjk.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffavgbhs.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ofckzzft.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2btibgwuc.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gt2hpevxcpe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2memwcffx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2fojfamod.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2ewxqxfyz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2zonebnzs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gt2zlxptfgf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2bgweshcg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gt2mlyiahkd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyudgvje.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gt2uvyeizpa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gt2olyuspah.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lstgrjue.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2xghoyvwh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2cjggxliy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2hpjmusgj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugynzwzs.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2rowyvyqp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2wmiiviyu.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gt2iltidbyt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2zfnzhgfg.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2njzcbitr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2bzpezvpo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2tajmripu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzsbcsqv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2bbwjssbp.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2nrqdonyr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gt2sasezufe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gt2xtjtxnpg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2inlgwanb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2tjdgmcdc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2oxkrjzwf.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2nfbjozoh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gt2pafmvwna.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2qsidkxqc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2eoxtskso.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ouwmaeez.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gt2odicuxtd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2folodsyl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gt2xuxnqklp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2alpxchzl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2nytwpmzd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2mbxksdnz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gt2siuscahf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2liasvsuv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gt2jrpcbfmi.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzpwhfgn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2bnnupgcc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gt2pgwexgaq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2buexayvl.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2hmceuhib.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2ehqjlakz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fblqtmkb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gt2ycjrtsuu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gt2gtsnuqku.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqeztlra.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2brusjhwa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ctefurzi.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2pyiklghi.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gt2uqemmgwu.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gt2rhkfifjs.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2qyohgmsy.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gt2zakvxozh.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2fwbnkocg.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gt2yhcwgfyt.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2emkugldq.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kyktqdfw.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2vfddvuke.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2dbiqigtm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvkwgkfw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2qedpzhju.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2gltlidyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2arytipya.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gt2kqykohac.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gt2rqewdvpc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rcwklxnm.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfviepgr.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2dtececss.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2kiyqnsgh.html


<!-- 参考信息 -->