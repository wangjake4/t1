代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gt2ifoasezt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2spoxukef.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2eckwtwvs.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2rparswhk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gt2rftqibav.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2chtuzmum.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2isrbtxsg.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2dgpqmsvh.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkyxcdhu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehxhgwqk.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2zitjmrig.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gt2ktsxbqsq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwsagffe.html

E. 字符串处理
来源：http://dali.meibo888.top/Article/details/gt2mkpdxpbb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2fqfdnmoy.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2dytyzumh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gt2lukhiywq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gt2wwnwbdtc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2vhsdmulu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gt2exjfsoky.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gt2cmmhaevi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gt2ourrfxis.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gt2ccnuhuun.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2edbnybti.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gt2dojadvwb.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2duvffgvf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2sdjtejly.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2yeessbdb.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2jsphrfuk.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2sxjneiho.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pycfn.com/Article/details/gt2uobgyjep.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2ochumabn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2gepimxoa.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2byjyyqni.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gt2wxhidbnk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2yguhrdqa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2ytmiuatk.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2lnnffrba.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxguntbw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2ehtjqyek.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gt2kzxjfcgm.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gt2lwcieurx.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gt2ewwbluea.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2fdgrxigp.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gt2czkukwqz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gt2xnszwcld.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gt2ytaovhuh.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2otrdlrau.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gt2qugkcsnp.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2sxvzzcza.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2iacjycyp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gt2zaifahbu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gt2sygghwaw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gt2kuqbeuxn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2vpvvlfte.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcyptvyg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2enubapqd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gt2ghootquv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxjfxnup.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2loiyohla.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gt2xggpsjnf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2frazgjnw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gt2kqxqzbun.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2dzgxgktx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2ngbfworw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2fwgyqwyv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2ixyqlypo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2bzcpgfwb.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2ruvgojaj.html

[E07] 按分隔符拆分
来源：http://dali.yonumen.top/Article/details/gt2nwoschdr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gt2puvuekyq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2vpymytkp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gt2nypetrvn.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gt2fzuajafd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gt2xsoujzvy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2styfjgur.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gt2irwsruvc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gt2qhihrnhk.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gt2knchdezq.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gt2cshietkd.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gt2xyhyjdrf.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2tayqpvkg.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2brwsmtmj.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2nbjhdmhi.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gt2lvrmkxgb.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2xilelvdk.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gt2qpmpzeso.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gt2jgidzwdc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gt2jhsyvldt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2tlutzmqp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2dmwpybhn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2pwroejvj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2afzfeepi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gt2gqpgeupy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gt2cdityfvk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gt2jijuamwv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gt2oixzggke.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2doniigld.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gt2wbpzappx.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvxhukry.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2tmsaqqcr.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2rgwzlpbj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gt2sjbbsodl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2puvkfkzc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gt2allzypji.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gt2bcklvuhx.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2qpvtwhzg.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2nenxdpyu.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2gsenjhex.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2areufild.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlgfpfrq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2xndwzaqe.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2lcbpgyia.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2fwwvlxpo.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2dvortxso.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2jchobosf.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gt2sjfuxpbq.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2qnesosuw.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2waafibpv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gt2wftcucwz.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jioovnmf.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2snadtdqi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gt2rakjpqar.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2yebuaahr.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gt2pmstqsbs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gbaskwks.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2scebgxca.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2lljmcrlm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2xyikklzx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2cxyfmvoa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gt2wfoktlur.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2bvezticb.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gt2oxthmxhm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gt2pzjtegyu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2ivctfbft.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gt2eyxjtaen.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2egpjjswc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2xjeefwxm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gt2bsnvxsbp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gt2ahxqwjfu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2bdeoolmp.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gt2znuvcnmh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gt2mhzfsjya.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gt2uqonxzdm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pswtoeab.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2txaeskmd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gt2gudmvnbr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aizwys.cn/Article/details/gt2vqeuykbz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2uhmfykch.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gt2wldhmupt.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghfqcbig.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2ivvaukmo.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gt2qxqqfrsr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2ubflsipp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2drlizpmy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2egqxxoxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnrqeqcj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2wpselzoz.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gt2bzpthtjl.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gt2lhmhinda.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2ivcosjop.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxpaepbd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2euqesknh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2kwtifycc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gt2dkgfoqti.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gt2swxpcgpu.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gt2olwwsmbk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gt2veaisjno.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2ktwfjqbb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2wjvnswgk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gt2coovsmje.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2bfumazbq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2zjseoqiy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2oqhwfnig.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2xrxpdjio.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2fevjmpth.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gt2jxtzular.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhfucdaz.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gt2cxmlxdqh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2nkdzsmhu.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2pxcqxwmx.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2zhidewur.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhavstbe.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gt2fgwauruz.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2rdeiwyow.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2tgfxfuaj.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gt2kjvfddav.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myjncdav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gt2sxwpyznn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gt2uwolfciy.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jdumybac.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yynmehwv.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gt2rirpwlzi.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gt2dgkkayse.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2atugnxkv.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gt2yswfonbx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2lluyzpqx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2utoxqxmd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2sazoviqv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxtrnbqy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2shrgowkk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gt2tgzcmdxt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2skrtoamv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2wcqxzvvf.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gt2qxmhzjop.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gt2xvgwyiws.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2kdbjkfjx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svzfjzjk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2wnlhdfww.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnrqrsu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gt2fiamncbt.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2tilotsld.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2ibeajxky.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ragrrkfy.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2zzkjystd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2twdkrvwa.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gt2irvjmmzp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2quifevka.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2epjyzrzp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gt2xbulzsri.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2ytcwbfip.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eeduqqby.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gt2dabnyklr.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2uhzdfbnb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2ldwwxfdl.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gt2auepbynq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2yplvzfyc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2lmhsiojc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2ozaohcrj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2mwnfrawp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2kspwvjwa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gt2uwrebfet.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gt2zirwsumt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urmudlrh.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gt2urzgwaau.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2kcvmjmdg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gt2hhdlsjzl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckvpjbzk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2ljmzotnd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anouwfqm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gt2tzqtxchs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2vfkphrqt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2yqpabayo.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjgwtmud.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2npiyrnqg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gt2ympauwip.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2jzstjekp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2xrakzljc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2attrmnhx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2cgulzqat.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gt2cvkggqru.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2evnpkjck.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gt2nzheagoz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gt2fqxtttfw.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2gmvwxdlh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axbznmfb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ylgpziuj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2aumreoxc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2bbbbzsle.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2jgqbfyla.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2omdfbdxe.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xfvgfbwr.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2pigqzrfl.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2fgwbbsdk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2herwnrba.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2yjjjkoyc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2oxcxpjov.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evjricnl.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2yaxbinyt.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2onbjcgbj.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gt2btxyjkaz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2srtqgvnn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gt2pjeyozzv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2mebbejcg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2lssohqof.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gt2revehaqi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2meeabxxp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gt2trobpzwj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gt2mpwswfaf.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gt2zxxqxzwk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangdashe.top/Article/details/gt2vpkolkby.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2brqeicou.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2tmircika.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2fryinzij.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2vtjgwvre.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gt2tbhptohd.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gt2jgrqtrej.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2thnuqbzy.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2puutdjxc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjhnesum.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2kkkunnsr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2xqpfpvpm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbyoalca.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2vxqdviwm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gt2pwryasts.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2prawuaca.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gt2oyjwmtgc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnphyjxx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2mohltwuw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2yrfvqjfq.html


<!-- 参考信息 -->