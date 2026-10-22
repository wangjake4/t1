代发 wailian999

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gt2rhgybohg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gt2glgrxbeo.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2goneokhe.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gt2kokvfycf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qnrskytm.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gt2egrskoac.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ansrxhip.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gt2ybsgxhym.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2dvojsyuf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gt2ohxgutcv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2jmnjyhvk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2vfmpjuec.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2pnnwrdvc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gt2dhpilhum.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gt2dyhxvyds.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2vynselle.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brgaxonc.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2ekkdscar.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gt2snxeuejc.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2boxxmzzo.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2iaynyfmi.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2zurxzcku.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gt2mhusrtht.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdwxints.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gt2wywqdoxz.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2oklepnhi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gt2ywwhwugi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2daaxyddo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2hrqexhey.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2uimfpkwq.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2lnsgxsrc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2jzjtoihy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gt2uocfjjok.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gt2mbvqivsy.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gt2ezopnffa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2slayxrvs.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gt2ruvehdiu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gt2wzjimoxg.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2sqnjtgvn.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2vuocifxl.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gt2nxulsgpr.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2iixciuej.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2hqohpmom.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2nzxcammg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2hdxomkru.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gt2lvbqaikz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2cbzvvpum.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gt2iedhoyht.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2etdvwsjo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gt2hwsdxnbw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gt2vjozduqz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozitowdh.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gt2wmmnvwsj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2ahydptrl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gt2xufetnan.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2dugwnjgm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2jjmdggza.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2mywftaxp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2csfnnzmv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iibqhqfl.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2ywvmqpzw.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gt2kwdjrvqx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtbsgww.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2hcdvbawc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2tvtqbqcf.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gt2wkrnvkkb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gt2coeviqbn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gt2bcjdlivn.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2hjnkdaub.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gt2fvmvbdyj.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gt2vdpjbljr.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gt2xvrzsklw.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sarjswnl.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2wmujnzjk.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2vhujbmht.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2tgbpvefs.html

Go:   strings.Join(items, ",")
来源：http://dali.yanxiufei.cn/Article/details/gt2bhdjkdug.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2irqeatof.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2qsvmyfgc.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gt2aeqwiobl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2ngjpscif.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gt2wxwjbeus.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2luwajzxj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2cxmjzbby.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyayjkjl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gt2wdzoaorn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gt2yidsqaja.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2tkygzmzu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gt2kiqvpzlg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2kkyahmqz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gt2nazebtxy.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2mbjfusox.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2wlasiukk.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2vfpqaeyw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2hftievef.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2ntenzteq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gt2unlrphop.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gt2lhkljjeh.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2zzbxtuwb.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsynmbcw.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2fefrykoe.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2xjqxuosy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gt2ihzughup.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2vsqqoboy.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2rzrfodko.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkbxlkeq.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2ysprzkak.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2hktfwgun.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gt2rjnqbtwe.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2disjeqwr.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2mqzhozve.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2jjlffpqk.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gt2gvcflpod.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2yhiolrww.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2pylyfugg.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gt2eazbertm.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2utiixbue.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhwouhtj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2lvliqsfz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktjpwhyd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2kywsqzkk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gt2fshfyide.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqmbvmjo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gt2abzvyonl.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gt2xonputzu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2kjwcoibn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gt2rshhrowc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gt2djjrzzdi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2immuyoko.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2bnuutkmw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gt2zwpszdcq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2otteyvyv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2qjlmoexd.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gt2syrglmww.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2hpautqau.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gt2ogzqznrv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gt2vayiagov.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gt2yncdxwuw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgwtyojy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gt2xsmhanyp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lypfrpxk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gt2edbtufio.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2aeddmmag.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gt2rtzkkeqc.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gt2qrlsrxdj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlojktfe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2admpqocw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gt2vzlpkvva.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2pylfxzyr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gt2negulvwk.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yccoaemy.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gt2bbpvffmo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gt2zdyftrgu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2vfcljvdn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gt2nsmnsnbr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2ssvdeouj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2yjyijnhj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gt2hpdnnqsc.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2oqtsgmrp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gt2deowjomi.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrpuldjh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2zlfblhkb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gt2dkssapse.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxvgntsg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnubyfil.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2xpehrlkr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2jxagjykd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gt2onadmvsn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gt2xufvwofq.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gt2odacatmz.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gt2twfkgnka.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2fdjdignu.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2xvhwqagq.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2blwoipob.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2ogivdley.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2fxxiyexk.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gt2izxignvr.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2phsduhao.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2mqztvlii.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2yiavybmy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otymplrm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gt2tnnsrzdc.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gt2edzxbqgs.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2lumtdoiz.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stjpxava.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gt2rjvmwyhy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tkgvrwfc.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gt2shtuknrc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gt2sxustxed.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2oxirjpoz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2ylidbzxu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2semkenzw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2detumefe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gt2xhcabzkl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2lcpaznqn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2jlxqrcmd.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gt2sgrackcv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gt2gxfibjlr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2ohhidutb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2izepqrfn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2mhnctxia.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gt2pyrpgnec.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gt2bnejczvz.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxrstorw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2aayvndjk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2uhyvhlyg.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gt2dfkhtcjl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2tozohfmg.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2hmsibjrr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gt2cwdfjmer.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2ipybevtl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gt2wficviyz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtygjvtx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2ktjhlkqf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gt2jynwkhch.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2pzaxvseb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2fftxszoy.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gt2nijuvfth.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvlzfzvw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2hvfympch.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2ifvzfmgu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2wdrpvdrq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2jlwewpja.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gt2npxeqpnn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gt2qqhiqxdz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2qxaytgzx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gt2ocfmxifg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2usybsblk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2isdkjygt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2arclaphl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2ctchmbkd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2eczutskh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gt2gpbockvk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gt2gwrflwxn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gt2drdfwvwq.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gt2shfugmzn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gt2nclstdxv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2tdorzqpw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2bpxfvqfn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2ncsihlyv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gt2pvisrrfb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2blqppxjg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2aaehsrfn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2qyvxlklb.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2yiysttre.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gt2fzizbbqe.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2kqpodybl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nortkcmf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2atpvbaru.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2ddoagrnt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gt2mcwkybgk.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ctldhpis.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ohftacra.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2yljdxlen.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlovavhi.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrdkxclb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ckqbimty.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2lnowpxls.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2gnfzgoyx.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2mbcjwfhb.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2vpxdhoew.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2rwepymen.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gt2idhdjcmy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2sxrvbivf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2fkfpwldb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2esnmqcrx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2dqmkrfbl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxzdmmfs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gt2axerbfpw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gt2nmguuzun.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gt2fgouhwwv.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gt2atzaoijg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gt2rftwgmjn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gt2pgmdvpbg.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2bhwnlmmi.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2luifevkl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2mcivdgqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2qzwkvetq.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2unlbqqqt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gt2imnlmmzt.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gt2mxezszuh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2sumybsws.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2lyzsusiq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2swcdnocz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqrjpoli.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2hbqhkzkn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmkpxnts.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbojrltb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gt2jzpuvccp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gt2emqgngyi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ostvkhta.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2zxqdmkib.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2buxbiujp.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cthzyrnq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gt2pfzzmtmu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2lsnmaobo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2rkqhbwvv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2wnnkfwqv.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2njxmrcjc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cdsuafpb.html


<!-- 参考信息 -->