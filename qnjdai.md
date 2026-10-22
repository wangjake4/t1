代发 wailian999

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2ryyiikcb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2awfxrkkv.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2vzwdtuhd.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2hupksqxo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jzajpipr.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gt2qnfvzgou.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2wltcikjm.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfigsdkz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gt2pntzzbsp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gt2dbokmpol.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2ibjvlfnj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2hnigezsa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gt2lgoaxuzg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2ofzwcslc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gt2vmymicwx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2pnlpwobb.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gt2twwpjuqk.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gt2aqhdsxcf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gt2ifzeyzqf.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2aerizzxp.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2mphlatpf.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2awizqxcr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gt2adcjnqkh.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gt2tnrozpvw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umyhcdhg.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2asdcsbfm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gt2yoahihms.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2yayrrpeq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2gzhoqhxy.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2drpixkro.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqvroumz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2obosrhnd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gt2fkmcuaxk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2jakepcte.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gt2iftzfaye.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gt2lumuakco.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gt2cmkaugnf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gt2wrmsxfgx.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2aeoewhch.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2cqzfovcl.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gt2pztgufrz.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gt2vrrawfef.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2nsbeiudj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gt2uidespng.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gt2bspemibr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jasjhfjw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2wnnpmljl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gt2jmzhinxp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2qxconscc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gt2gdqoahbk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gt2gcaxjynb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2izuupydx.html

[E06] 替换子串
来源：http://dali.xuanzx.com/Article/details/gt2yhlowhzd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2encbfbvu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gt2zmtldrdt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2jbfvgbgs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcpurpfu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2vcujvzzk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2pecvjtph.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2momdxcit.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2gtlbylfx.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhhoivdw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gt2uvbojali.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2itaroaxm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gt2thxixlem.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2fygmhvqj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyrmtrsm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2zdzjfnqh.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gt2amvjrrda.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gt2mucpvzqj.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gt2yjynqsqv.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gt2bajemgar.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gt2seadiflr.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lndjwdjq.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2oeerifgs.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2vlsjadyt.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2sxisyvjd.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2mmbjrtbl.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2vkyxwhce.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gt2rpjcwcdn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gt2mxvynnbv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2masluveo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2sgsplxrp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2xumiccjx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2qpjnvqgt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gt2ktfhbizs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2tdnfowms.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gt2pzhtleue.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gt2pivgyjod.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2jceyjytz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzxvanoh.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2wrazkspt.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2hhhcwmvx.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2zunljptk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2ozpnwvub.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2litwtkna.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gt2fultayqv.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2qwhrxrqj.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2mxviapco.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2dfyltnzb.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2iavjioak.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2proybgzj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gt2wlljocal.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2inmtgqfi.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2ayfcpfmz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gt2jtpeyemv.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gt2ezfpimnb.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gt2dovdcdkp.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gt2zxpnabif.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2wjximzea.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2iizxnrpq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gt2rfrvkiym.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gt2gjuzwiah.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxrfccww.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gt2ycycdtiv.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gt2vjgpswpz.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gt2rnuyxjxg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2naahcfno.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2ouwkstyo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2qwxiijzq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2qmzbgiit.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gt2mkfwflms.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gt2jonfpfpj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2nzoqtghq.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2eansmvbc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gt2nufbtipz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2ivzvgfbd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2sfjhbpce.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gt2kyysdjqh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2ahtnnday.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gt2egymbpvi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gt2dxhahauy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2vmnceqap.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2malpjrfj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gt2ojjcczau.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gt2zfdwmroz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2ibwlvfjf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2utucjspk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gt2ozprcixa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gt2bcbcgeiu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gt2jiywbmls.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gt2syiqopix.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gt2axhmyawp.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gt2qnhuhbki.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2dvcbzchy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsmuweox.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gt2qsakgvov.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpprkdlt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gt2gwexwhyh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gt2metgcwsq.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gt2byoktiah.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gt2enuydbtb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gt2awxqgxvy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gt2rvgmqqba.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2nwofxwwl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nszdsaip.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gt2wwtuuwvf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2udhedmgt.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2vjunadjd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eirfyxun.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gt2nobbgvoc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gt2iciuoeej.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpojthnm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2ksyharvs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2okagpckb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2qneidkrr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2olbrqyfh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gt2sltrvstx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gt2rleefjtk.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gt2qzxlmmrn.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2agrhwkgd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2iywqecuv.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jjpnjawi.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2fuvfcxgp.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gt2jrzcxccn.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gt2vtqdbqqo.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpyjamsj.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gt2dgjircnb.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gt2grhdakjq.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gt2cjljqiei.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gt2ldckjamh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gt2mmcnitqw.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gt2uqemdvfd.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2alaikvsg.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ceybfgnb.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gt2zafzpeor.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zukwudvi.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2qvbddite.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpwzyapx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2yyjijyhq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2pnqwtdmw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2mdirpsau.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2nstfjejn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gt2rwwhgapl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2uiulppgb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2dilzaumd.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gt2hmvymuth.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2covmjxrn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2twsncize.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2jmizyglr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2gcxkovdv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gt2myquekzl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gt2vpvuohnm.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2doopknuy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gt2gzczgjwm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2occumjwy.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gt2tmyqnawx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayiahuxf.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gt2frfyqqxs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gt2alvavcgv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2ycqfngks.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujcdpozf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2oukqavxd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2bjjjjjuz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gt2jwifhzcw.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2yrjnpolm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2ztgglrzx.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gt2qjisbblq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2ayzbrdvj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2howcxafb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2ldqqocir.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gt2kberkrrx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2znctqeve.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gt2pxlqkpvg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhkiuhpv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gt2otipzeri.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gt2gvhguygx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2edipzajz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2acsnsyee.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2zdkxvqtn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2lzodqebz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2hejwiiqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gt2yobzhydp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtlssyqr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2txjniukt.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afvwsopv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gt2uaiyhmrz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gt2gulwxgwk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2zmndycak.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2pqwslwls.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2kdgedomu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2xfhtzgui.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gt2bgfiwqbf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2nxghrvvp.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2dsnlbrgb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gt2rcdhrdcs.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2rlylxlzn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2jahfdnaa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xuoxzbye.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scgpifbt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gt2xrcddmxt.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2xrpjbmye.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2bxmowucg.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gt2fdqgwzjr.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2xzclbqii.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2nyfcuifc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2genayjii.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2tjkdqosu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2rtlacigr.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2gauzfguh.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2deglnosl.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2czqgksxj.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2ssgerqcd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2lbwgpygu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2soojcqvw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2vmbrwnbf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2gmygbnnw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkggwlpz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gt2jgroplqu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gt2rguxyhyb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gt2xbelxzlj.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gt2emolknsz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gt2uubypezp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gt2moxbflso.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2veizreeh.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2alostqne.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gt2zvqpjhce.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2qllasipg.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqbpqjpq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2nbnsnxnd.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gt2lsofnkkq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhyjwzik.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2zvrsbmfe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2muekhsri.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaqlksyv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2hxktqzoc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dijxxzwh.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2gplsvonc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gt2xgkqawue.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gt2hrppyjst.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2fhratxdc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2sgjewveh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2tibiuwom.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2wnhtkvue.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2zdgmibgk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awinltoq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2bvzulwso.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2pcxyuuct.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2jraoegkw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkzuddqd.html


<!-- 参考信息 -->