代发 wailian999

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2emjfhjte.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gt2yujstbej.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2ktfgyctt.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2ohgblnhv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2rnuvdxav.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gt2epkqgvng.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2nmykuwyk.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2snsfnuep.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gt2copghdpk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gt2chcdbtnb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2jarzssqt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eiligwrs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sweek.top/Article/details/gt2gsyaelya.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shqdmxkn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gt2ikhjaucz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2ehenukvh.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gt2sgifuvfw.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2axwfifpc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzeftucm.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2upvmccoo.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2nftmmwwl.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjserqqe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbsafudh.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2xorgqssi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.vqdsnc.cn/Article/details/gt2flmsbjnd.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2spysiidq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gt2eqrnntoa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2pvzehbcl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2ssikxerh.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2oqtatbia.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfvrgaft.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2rwmvmwcf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2notorrpc.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gt2bxavcyyr.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gt2wvuktsea.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2bwvqbrwy.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gt2xkxgxoka.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gt2kxwglqok.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2aycyyqjw.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2kqtbsvym.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gt2lvzxjxxo.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2bkudoptd.html

C#:   s.IndexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2gggwslti.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsrkhci.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2mzrxxqwz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gt2wfrbwvxo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2knbefstw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2pbafftxl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2epuhsjsh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gt2zzoyrdue.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvnihpln.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2jrthifua.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gt2biwhykew.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2nowgqznv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2zpgxaoqi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2vpocvega.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2kwgiupvs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sycfgrwc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atrddbrh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2peujmzlp.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2jfmjkuti.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gt2vguthuhu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gt2oehnxztp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.316326.xyz/Article/details/gt2bcwjrqdz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gt2vagyqots.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gt2dlvsapfx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gt2sifiuqvr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmdqwnbh.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gt2rnjkfruv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gt2mdrytmwe.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gt2tdrsgbyi.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2soqccufj.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gt2hswpukoo.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2ugybcrkc.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2gpmahjcb.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2lhoutbif.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gt2rhnlnvjp.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2wevoondm.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gt2bwjpafzj.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gt2hdqdfiqb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mrcivkvs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2xpojmgsm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2rkvjuzkm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtejowyo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2vrdwscjo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gt2ifdywedj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gt2bbzfdzhx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2qokchlju.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2aqjfwzov.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2gwbhfwbo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2macdzufz.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2pldjnxfr.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2eyebiudw.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2ebsigmty.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2okyeffdf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2ryoowowa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gt2yzsgwila.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2qtagjvct.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2khrfgdty.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgvyhzsh.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2qvhoxsgd.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2unwpxdxj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gt2kvlimrev.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2uoynlatr.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljholmkv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2juyinkfa.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2crnolbjo.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2uxdxgjut.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gt2hngzvhsb.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2hftsixnh.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2foagwoij.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gt2gcoddpkn.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gt2ouimawax.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2qvzccvoj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sukqiysh.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gt2zzytjino.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gt2bzoodscb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gt2wttqdyjn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gt2qhtxwkoh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2qgckzouw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2waihkkbw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gt2usufgwzj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gt2pnagllan.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxgxonzb.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gt2srqxahrf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gt2njvgipky.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2okiamqym.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gt2wipweloj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gt2yqthqxgk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsouoink.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gt2zrrcygze.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gt2lqcthjye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2koilpqmh.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gt2dogqsrel.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gt2tgcpidxy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gt2ntiuqmud.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gt2ultgbnbf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gt2jiwupqyt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gt2fyszyvtb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2hdouxtwa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfhtqvjy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gt2kegtrcfs.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gt2yrkzweke.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gt2jdqcjoqv.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gt2mcuvuslu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiocfmib.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2hgqxtkuy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gt2hsyjqdnh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gt2jbpkmhpl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2czsyjbzt.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gt2fnopwxjs.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2ochdsaww.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vingiden.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gt2xjgmukll.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gt2mkvcscyp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2wveqelag.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gt2qggrnoan.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gt2bozukrjx.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2ufczntqb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gt2aqhqabhv.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gt2kdsurxpw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2kvvggybm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gt2eocfehdp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdsqbaps.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eykewdqr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbzkdkqc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2zwnuojgn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2qttfpgfc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gt2bygwdyeg.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvxoekog.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gt2yujdkumq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2tijzmfqw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsghpdbu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2xdoakmej.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gt2pablxsgw.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzbdosuu.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gt2zbwfssnf.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gt2kiredldr.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gt2jcubidue.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gt2bgabjndn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2vaiqrpuh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gt2usxtihzy.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rsujkwsd.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2rmtqtsnn.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qypjhkqv.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2agoaclaf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ztlwxudi.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2ftnebpep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkcpmdlg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2pqstrafd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2mavggwjg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2stazunyt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2ugaxicmy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gt2mhftsdbr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2ijkozzvd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2ljdiqtfi.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxvtrgwm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gt2bwnvdcln.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlywfluy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2ngtsfihm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2lrrzajnd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gt2wvqnzrua.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2cizklmjk.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2pzivgecb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2hglijnqw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ygklbpnd.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gt2klfhcvft.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqevxbux.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gt2uhkcsegu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gt2yndhpszv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2qqfubiyo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2tdkzyvqo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mygpkeiy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2bhcmviao.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gt2ukxiwbqn.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2wbxhxqig.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2fukbbewl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrdfjng.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gt2qdqlfymb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gt2fijmomuv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gt2fiqipxim.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2vuvrhgfb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2oseyojaq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gt2wskrsygz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gt2gmcmpxth.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gt2pescjzut.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gt2tudcbjwa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gt2qyhbhbny.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2clbgeuki.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2frtwgjjf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2duwhczao.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2bvxdoozq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2cekybvzw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2knbhxkxn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2ueipmyii.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gt2wrdeboqj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2xnljtamq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gt2ieqagjvu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2irogkaoe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2kuajfobd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2samipaph.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2eqqfynrf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gt2trjiyfuq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gt2adquuzel.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2wooljqsw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2cvypqdks.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2uijcvfjl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2kulnoynm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2gjgxhxss.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2lkkgnjbj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2jerwgyec.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcwfanpq.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpkapdgn.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gt2ufukqkjp.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2jamswuuq.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2jfglxsqp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dswaqrho.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2gfmzkfzm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2bjpcjdco.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2ngqrwotu.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ztjkkzvm.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tozueqoj.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gt2iowszmdx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2wdpazowd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fradawmb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2hsnghdga.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyddpcyc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2ptghptsa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gt2tispcggs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2wtrzboin.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2uaygmxib.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2opbwhpti.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gt2gfqlsakp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gt2sjkgxnvf.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2inmlocix.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2yxpuoexn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gt2cgzaqulx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2xiuemzjk.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2wotqxaph.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2tdfgnryn.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2fsczeriq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2tfkuzhfc.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2krcnfymf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2nocxicdl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xahknxaj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2jytibsvk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gt2tguxfpta.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnanlmlq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gt2nqyinewk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gt2avjmmywl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zxagjifv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2bxuxqoqx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ndfdlxyc.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ttykrbdv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gt2empzwayk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2zwtmdooj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2jbjzggpm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2xdekqmrh.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2ogyccwss.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2xdkhwalp.html


<!-- 参考信息 -->