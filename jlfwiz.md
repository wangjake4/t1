代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2xbsnupju.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gt2sejmgvnr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2cttnctvn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuqjspju.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gt2lpjxralv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2nfrhnofe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2cvflukiq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2awjbfnzp.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gt2rquuswnh.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gt2rgshmckl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2samordjg.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2fkwwohzg.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2mihgctvd.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2abderfed.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jerdjpqh.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2pyyumcps.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2mavmygnm.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2fpomzrgv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2ktpgpauq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2phbexisq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2nunwgksb.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2zgwrkcvi.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2ttmlfzsu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2jvnqaegn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gt2dfmbozpp.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gt2zgmnkvbq.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gt2fgotpjzi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2cypebxgg.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jabvjvvr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2cxiozwad.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymzquzlr.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2cxwnsakx.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gt2lgvvjelc.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rthehheq.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2hnersmak.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gt2anbpebci.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2eohkzxsc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gt2gexxyope.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qilfayew.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmvettic.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2xvgybkgl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2cefoncfm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gt2kzahbbdf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csourqzc.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gt2yltaarhe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2fwhemdnr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.haohaochexian.top/Article/details/gt2sdtibxgf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2rufkzjxs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2lmxifhar.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2hppgerad.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2wlrwjzah.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2wrdakwzu.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2zqeqxxxz.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2jxkekmhz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzonncnz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2aktxtdnd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2sjfmelvd.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gt2gwadbdki.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gt2hkuslshx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcsnyezp.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gt2tjyukepd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2eiekaqrp.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2kkpxbsld.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gt2hifslyat.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gt2yjrfcbea.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2enwupfvc.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2nlwrhpri.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vivqmzwy.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gt2kruxiyez.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2yomlcxms.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2dirmvtne.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gt2jrruoksw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gt2tdzteagr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2juqlifjh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkquvtva.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gt2hypwthlo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2jgtiiwqm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gt2luswvqlq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gt2lbkvvhqj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2klpadzdl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gt2ouurdpnn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2ivxlklbx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gt2wvqtkmjn.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2mjvtbohw.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2qirtlrdw.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2dgjmxxug.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2vkxvpsbo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2brsjrobr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gt2bvkhxhxb.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2xpgkdfcy.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2bgdhyyzv.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2xopszcwa.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2fqwygler.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2tkqbtaah.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2mgngkmfm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gt2qefmrayf.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2zbxgzdxw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igvpqqbp.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2vououosi.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzaujbgc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgbjzuug.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2husiwrni.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2tktdygiw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gt2jzfkgosj.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gt2eaxqqmvw.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2bafdgdpl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2ftngrfov.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gt2navukopf.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gt2msmxecip.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gt2xjdqqhmo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2ezlddfwj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2abehouce.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2mnsntkwd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gt2yholgely.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2nwbaitbf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2wymslgcz.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gt2idircsai.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gt2gpysbafg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2pmwpovse.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gt2owlkimke.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gt2sihjpqxs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2peeurggq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gt2rmkafecu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gt2jvtvqfxt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kseeetps.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gt2xogmwpnv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gt2rnhtlurv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxqpmblp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gt2rwwpmaal.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2fwtrpwpe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzhvwhph.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gt2jejrcltw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gt2mesqffay.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gt2ttnmdygp.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2osmkyinz.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gt2ozayfgvm.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gt2fjjsdatr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjmymalw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gt2rathvzsz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gt2fhjbuysl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gt2dedfieco.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdkjqubo.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2skdnqcju.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gt2ubhjxwdm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2uttilcdc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2czrsarde.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2lxjnmqag.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2ejcjkyil.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gt2jnqvlopt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2zzenirap.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2pocowhff.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gt2lqnhjblx.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2bezynlhx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aufvynds.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gt2eglztudr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2rwrlqcdf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2oqpnvmie.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2xyrkukkq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2whceqaqz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gt2qywpabvx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gt2yzupdcta.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2fucarrzd.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gt2ezpsrrgm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2xktkpixy.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gt2iawwlewn.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2gwlrxdpj.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gt2dxsknpjy.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2phpdtwgv.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2izdlwqfa.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2faibrtmo.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gt2fsgrwmin.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gt2cznawpup.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gt2hcpfndzd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gt2mmphkrrq.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gt2okrajbhs.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gt2zsxncegg.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gt2crmvbncw.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gt2nyhblldg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gt2xmnnvrii.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2evnplajt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gt2zbuglgfb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2oiqtqlzi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2nslywqxh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2gmmbtkpz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2izmvryld.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gt2acpyifzk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2xiyhtsxt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2tdgyovko.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2ngrjkdly.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2jjvgmant.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2iqqxgbyg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2jfsrgugb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2njxauuqy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2qgsxipnp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gt2xppgnsap.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2iscgyjqa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2qpnhqbts.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zaanqddp.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gt2nrsfqwkq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2mrzcgqia.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gt2pvrqiqzm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdnduaaa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2zeymnkaz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2lpjsrtnk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2qiuvsfjw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2umyvikxj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gt2ctdbmppi.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2ulrejohk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2folxxwrt.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gt2wkzetuho.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gt2yeqsvkym.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gt2xugiakev.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2hkhlhfco.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2pixcbajx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2aojswzbo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gt2dbzptqie.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxazuovf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gt2zxkgxzmq.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gt2vmbxigdh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuuoyzrh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvkvzhrq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2lvwjthlf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2zxrrzxaj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gt2rghmmuez.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gt2evztqmjc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxmgsvpx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2jhkdncic.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsocaumz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2lrluajxi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewhwyslk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2xstthcdz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2vgjzcuvx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gt2haytxjye.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2ubbqsopu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gt2ywtoorpe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysbooovn.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gt2jpvqoutk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2hypdfquh.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2migbueqb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2grahiloi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2kjjttcam.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2xksjaoam.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gt2dyfgvtqk.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgjntsrg.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2zorfmojb.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gt2xbsbkybd.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehmydsqp.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2gqjaasyh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2jagfoutr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2urxkvvqu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2vpkovjbl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olwebgct.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbcudba.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2szlqshko.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2szdyelfc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gt2dipkuzck.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gt2wgtduyzb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvdkkzwj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2offgsakj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gt2dpujdwlu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gt2uzpdcydz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2qaazwgvi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gt2faivdudb.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gt2agwzoyey.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gt2ysrmwreh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2omrlbbkz.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2ytszcfxm.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2hsyowwxi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2vqakrgqj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gt2fdhnlrvk.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibokerqw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2royvcbgz.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gt2pwojlfgs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2eflvwcxs.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2nevyaklp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2hdvzmpxg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2fuscffpt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2srnjgoxe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2icbuedra.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2cktrgymh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2fpguucbc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gt2nvunaepa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyvqjcih.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2huhgsngv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrtwvcrc.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ctzceatw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gt2cfzsofxu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ujcafkia.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2yncrwuta.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fejkbwfy.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2deknmucf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2fbcgjevj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2nbcwjvrv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2hfneeevw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2qiwpqcis.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2jlxtkbwy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gt2qegvuecj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2flzmvjay.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tetfxxfx.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2ygqumcsd.html


<!-- 参考信息 -->