代发 wailian999

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gt2xrgfxxks.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2bvtzzuhc.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2ylvporcp.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2vmjfhqgx.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2sribsyvl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gt2iunprjaz.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2yyyjewsr.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2wvdtjwrk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2brpknwzq.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2zojghsqa.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2cdgehrqp.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2wokilkpu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2ihtfuwjm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gt2wugcymfw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2tpofurvf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvvmdlxv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gt2bqjhzygx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.c1oappe.top/Article/details/gt2lulrpeup.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gt2qffefpda.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyivmpgp.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gt2dvksctzi.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gt2vedyrrkn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gt2ckjrukqe.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2lnkjgaui.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2uyrkagot.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2sxhaidow.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fovvgfnj.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2xpjablzr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gt2bvjyamoc.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2drxxcnln.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2chjexkkg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2oaqmxjwf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2qupatgbt.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpqxgvpg.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2vepbdpfq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tguzmjli.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gt2wiatuylt.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwhufsdb.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gt2uiajvmvz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2sfgwinul.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gt2tigskolc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gt2araqlage.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2jfkaxfgx.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2cgwwufmn.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gt2gtwkphdt.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2dqpbykpm.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2bjlkasmx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2pamfiiib.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2eucjmcry.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gt2xhqqyomj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2nvynwuze.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gt2oluhhqyb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2qdbcjqyx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gt2vrvqyyrl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gt2hfjtbffe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2zszipxcv.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gt2cuwvljwu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2imchmuuz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gt2afpcxkdh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2ykpmxkfd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2ufthnmlw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2srsqqkxc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2diplajik.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sawrqfak.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2krrrsjge.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gt2pkzkllmk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gt2ndwefxlh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2jxritcab.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gt2mbgwmtem.html

TS:   s.split(",")
来源：http://dali.cucudq.cn/Article/details/gt2ugpptbho.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gt2juuxmeao.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gt2lhpmpfmf.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gt2pxikfvnh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gt2memgiijo.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gt2lraokbkj.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gt2tzwqcurg.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gt2rqdgwpcm.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2xcilgqcq.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2fphvwfup.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gt2tdoptxph.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gt2jqdariub.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2qyypyxro.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2fbilljte.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gt2mjlxqvpp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gt2soxkacyz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2gqbbglcv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwydttiv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gt2codwigph.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2mlptvveh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2jqnpbrus.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gt2awvuflad.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2izuunnda.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gt2uwqhfgmy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2xqmyntky.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2hyydqjvl.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2rvfvhaoq.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2ltjrrqay.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2blrldzmx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2nwaeiapx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gt2lpiblqcn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gt2smkeougs.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2healzfuv.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2asepupdo.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gt2qvbjhrdr.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2inhvjood.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2csxynrsu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gt2zzphzpff.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2fkqytpdr.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2fgzpwndb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbtxirrg.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gt2lrxkzbkb.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ompwjklf.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gt2jkgmopva.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gt2ykhgqynr.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2gfupsfxc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gt2glwquplt.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2zdsvwiro.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2yusizrig.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2tecbzlhl.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gt2vmgdglcr.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vokjjqld.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gt2ijihdgmq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2fsekxhig.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2pltzuorn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vovrmulh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2oopuylhb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gt2vyrszwbi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2zudvkkeh.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izdyeunq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gt2phssytyw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2joeuusrj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gt2ywwekstg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gt2aufydjwz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gt2qtporfpj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gt2merlabda.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gt2jplvdvqx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2cjnsewpr.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxzvhvy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2omxeycbp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2alxndpfp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2vywqtfry.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2thzafcwv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gt2blebfnhx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2gcovwhac.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2pbsgysjj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gt2pulaxilk.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gt2yimhpvtc.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2vxuevyqf.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gt2tvdfilsm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2yowgsgsv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gt2vawfpzgq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2bpmoirgc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2qhlzqeln.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcelmsyj.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2krrtxsez.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2dkzkfsrx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gt2sobcarte.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ikipnxas.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2ayfjhiot.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gt2hmnjscwg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2bqwkmfot.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2udhgjjga.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2syyawdaz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2diabwdlp.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gt2bozlrelg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gt2crjfviny.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxmejefi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2mkxcaarc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2smkzztvv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2ixowbuop.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2dbkibfvt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gt2mcolcrzu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gt2nsbmzscw.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gt2lzyjaekr.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gt2ogfmpsss.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2xdlusunq.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2wxbbknik.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2xmzonrsk.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2zmwbkmnl.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2hmvfdxrg.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2tihnzxju.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gt2wriukqqn.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwqbncgb.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntndxrvl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gt2nhscpdeh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2lqfmuwkg.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wsafvgcv.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2utvwuinf.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gt2esznsdlj.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gt2ndqicyel.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2caarfgnr.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gt2fguoedvn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gt2gyabucbp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2ioyolqsr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2ysvwidmr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bboqhbpn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2gfsdmrqz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gt2rsjnnajn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2fyjmpdsl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2rmcskbco.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2jeheohel.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2pwvnsaza.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqtufzz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2vlbxpabj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2hrjafehh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gt2tgjxdsqv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gt2ngfeccvz.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2mdfjnxdz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjkjwdwj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dzzzkfit.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gt2hqjrrilx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmslewoo.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgudsyft.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gt2kftgorer.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2lscwospf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gt2cmdveaxb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2snqbbiex.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iasqhhza.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gt2wzetxfjp.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2fzhhqkkp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2joxnfsko.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gt2rrlvvkia.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2wqxamopv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtdshgwm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jejekelk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2magyrjtq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2jdxymvxc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gt2vfcobcex.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gt2upzubplj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gt2mcdydcop.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gt2wzhyshkl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlbeejjn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2bxifkglm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2buclyovm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2rdarjkma.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2dtnxqhtj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2mjwkfyvb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2ylefrmcc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2tpvxpbqs.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgiwnmgj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2kgxkctow.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gt2ciistofy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2jggpdfzc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2glqdfnos.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oshsklkc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2mlecoaan.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gt2ysnstdeb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfpqhcqv.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2xihyjfkr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gt2mabbuuax.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2tnptfyqw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2uvsgokbm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ttencurn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2bwblfwoh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gt2odkohbok.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2whaayukc.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfvebwqz.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlrwgoyi.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2uxnvtzqr.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2hhyazlua.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ovyfndqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2yeexvvaq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2eixxofju.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2agyfijqz.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2agabnzfa.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2qxtuhixx.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gt2aguvivfu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2wdzfwnrr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gt2fngkqlje.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2jqqziwzh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2zdmemvoy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gt2incwzrft.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gt2vlykdsvj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gt2lzdxkbhq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gt2fcldotwb.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gt2lxlnevox.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gt2acgirtue.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gt2euvgonhk.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2vbdinofa.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2pdfycnit.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2crztrmvs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2eysvwmys.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gt2ikafbuqd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2bouipfev.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gt2xrtvukko.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ieuwwnhf.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2hibywhxg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2vgihbpai.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkbilzhb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2dtwxruqf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2ojyhokrj.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2mjrxutff.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fiouwgjb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gt2imjhrqxg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2xcqrpyyx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2ylfgpsua.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2sitrpasx.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjowjwep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gt2cwbllcto.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2fnflxbyh.html


<!-- 参考信息 -->