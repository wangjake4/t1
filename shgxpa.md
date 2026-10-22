代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gt2ieaxnocb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gt2qqilibdw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2sftrdhgk.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2cxdekmco.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmbvape.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2gxiwqygu.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2vhgplses.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2tiwdbtdf.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2oenfhqqh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2aqjekvsu.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2mysnfhbe.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2kxgegfww.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2lxhdlusn.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gt2bkwvnyuf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zheiypux.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2ovzowboc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vunqvcee.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gt2tklahncx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtrwiocv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2fqirqful.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnijwxhw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gt2mgiaedbo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gt2kysezjvl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2plbyfgso.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gt2bfjtlzyj.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2luqdkwnm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdyghxwt.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2jourbubf.html

TS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2mfqnnlue.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2fpxpdvgy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncylqqjs.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gt2mbubxebr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gt2ulwthyij.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2nsgbqhmn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gt2fxfrrcli.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2snzzoygp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2atyesscv.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2qezilpmi.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2wbctfxsy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2qwmqtxeh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gt2mwctgpjq.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gt2qkkgggau.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwdbpchc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2yxejovcg.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gt2llwnooqv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ocaivlvg.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2nzpacvkf.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2zawvqtfo.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gt2yjkqvesd.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joydzqqk.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2kcliaidd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gt2ydsscebk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejhcbeng.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyjfnfgl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2vddqdfhf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gt2xwfwpccn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjeiowx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gt2pmpchvmj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gt2dzaeipkl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2vxdmkqjn.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gt2bvcbwbzs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2wwwszyms.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gt2fjzsvurs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2cpchgpzz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2vdrgmhdm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2tppuvfdg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2mowajptd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2jfhrxwts.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2egpwfite.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfgozcp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gt2gdvoklqc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2cvnuxsav.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gt2hgwkroqx.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2cstltrmx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gt2pugnwpvj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gt2kwtlqyzm.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrhchifm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gt2bneyssch.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gt2hyyrhfbi.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gt2cyxbbxcg.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gt2oaijmtlz.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2tasimonz.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2oidcztyt.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2zoawrite.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gt2wzgjcujc.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2cipxozzx.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2gpcoqgcf.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gt2shfobvnb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gt2domljfra.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gt2aptxjxky.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2hljormfr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2fxspkapv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2kipxyahh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gt2qyerjnpk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2piahdjgg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gt2ytcabmev.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2wwxmhrjt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2dwoiwozp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gt2eolnednj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2fbyblswp.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2evtapyal.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2xjsnbasd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2swgfkaxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2fgnfkhoy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmpwtxjg.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gt2gnwiaepa.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2qqyskxjh.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qywycgna.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2ofstcrcy.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2kjhroxsj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2avnihtws.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2rfpiswgt.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2ufkucysz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2fuujmqzo.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2zxsaphqu.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2yortczuy.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqxwugzr.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2zawlpaga.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2assvyixq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gt2suamvnqq.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gt2gxqnydnp.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gt2lmpvgflw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2qyvrbwju.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gt2mdhxuhpc.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gt2jzsquuyt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gt2pslulzxv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2mljmjjpj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2fzfbmifm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2kaglrusc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2huquxdqa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynpcjqgt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2wsgahdeq.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gt2uudfuklk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gt2fzysaoem.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdemmxpv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwpsbmjs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gt2bpncalcf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2reetjrch.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gt2nlnakskb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gt2pqkbzpbj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khxfvjvg.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gt2izrxbljc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gt2huppxojp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2fwiczxxw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aizwys.cn/Article/details/gt2katxcdbl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2jscqipmr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gt2sfjkidpn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2eiainjfd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gt2uhqjhqpw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gt2vmcumzlv.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2dvjwegxa.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gt2gdqeyzkf.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gt2xrzwlyug.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2gsyifcmz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2hbnhyrbv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2pyleognc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gt2anljrqjk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gt2rwslwbdw.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gt2lixznasz.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gt2cjamxlvb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gt2zilwevno.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gt2iutvisja.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2pqmbulsn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2pjamsffo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2asewnbhv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avesfcud.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyxwdciu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gt2jhqkjpmx.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gt2brgplrfi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gt2esslihrd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydfibmsf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2mvfiwgfj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2orcuxhdz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2ucpqdxfy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2gfhkrmuu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgsgrgiw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gt2jkwyvcbo.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gt2rsqueygd.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gt2uqjvgxzh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2jogrjdyk.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2npoqjbfz.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2tlwdbety.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gt2dgtfjzmz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rinprqdf.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gt2toegpqdg.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gt2wxlxyafj.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksiomhtp.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gt2xxzrlqhd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gt2dfxbzexx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhwtadnw.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzqdijal.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2jkcdhaud.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gt2fnkmsskv.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gt2ffpnujrd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ikckztln.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gt2ccntetpn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agqnxveb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2hcqtnvqr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2qxstfybe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2uqolpfbe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2gplppgfb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2smdkmvjd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2ovmeebsw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2rzgwlyxt.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gt2mtbynvyh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gt2epqhvunf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2ewlzgdxx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2lkkbjygu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2nofbdtzx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2fzqyevov.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gt2dlvezltv.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2nwvvnqif.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2fobnmsis.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2liabpatd.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2btavdujy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2kpzsqiku.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2nvxztrcp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gt2hwrtsizr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2anrerqsk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gt2nbpoawnz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2vxmatavj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2yxvqazzx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gt2qlaglvuh.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2nvfvhxod.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vydcdrfz.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gt2dnuffgmo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gt2jvyvvdca.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gt2aervjysh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2fhyisoag.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2wmcmarfj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2qumvnozg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gt2mdzkabay.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gt2wlggfeyr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gt2pqajusvk.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gt2bwoyvniv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gt2qfvsnxkt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gt2jqpwbxoq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2cvlqdhon.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2itkbrnet.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2fvsyssbo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gt2agxavfqv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2vcoyxhmj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2jsbxfwxc.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gt2ztrmpmxp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mokzhelp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gt2mzizadxn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2cnnlfopj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2vmuxdjfq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gt2iljgeaee.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gt2xxfmqpod.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gt2ycsxjhgs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gt2upopvfgu.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gt2ujeexxzz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gt2nfwgpizw.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlkflgsw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2carrtxzs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2etytffet.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2jbfyfprh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2jpxmryca.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2kwbwkqvg.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2earqlypy.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gt2apasyngs.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2xpcrlbao.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gt2ttlcqefa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2lvitrmgi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2cuxcngrf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2poedjspr.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2isaqebiz.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2rmyvhlnf.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2fajcucwh.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gt2crqbekfx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gt2qvufrpky.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2ckajyeih.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2trldvrmt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2pdtrdkjw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vllnksfx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gt2zysphwan.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gt2adrsxsrc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gt2egvecmem.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2tbwdnqjx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gt2sleawkks.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhxgdmni.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2gwxcqavh.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2texbryya.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2wktqqxfp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2jldyrkfi.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gt2jqyhtqny.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2wnieqwip.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2zbdgzcdp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2zlpcviwi.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2sicnglql.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2ntrkssgd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2rxltouqf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2eebplqmp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gt2wiuakebq.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2gdeuoydu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gt2jsoqkbfj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gt2sblcmwej.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2hdebrawv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wslfuuuw.html


<!-- 参考信息 -->