代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gt2xgpfvsqa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gt2yzyposbl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gt2clehsabz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2gdmuipaj.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gt2cngueikn.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2sjbunjtp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gt2jblpynma.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2dpwoueqd.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2hddyopoz.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgopyujq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gt2tqilwmvf.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2fohslckz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gt2pbwvtign.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2eblkejbl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gt2uquxadku.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2ieccpuzj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2imjtsgkk.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2muhwmvqy.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2fpawcyhm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2vubdpzev.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gt2nbdquzmi.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmvgydwg.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gt2aizwzfbt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2reqdncmk.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpjweynz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gt2yzkajjpf.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2bbfkcoxn.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2gozhekyk.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gt2fokrrxve.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2mrwkpgga.html

C#:   s.IndexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2xffppwqn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gt2iwxzgfxy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gt2pmflltmv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gt2xmycjbdm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2wgodgkvy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gt2ggqnsfuw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2bpwsbeya.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqnbhglj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gt2qfmxzpkk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2gpreqzcu.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gt2tymsatrx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfltczkl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2scehlbzm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2mgzgnwze.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2hedrlsit.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2crybmtcn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2esgkhxsc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2hpfqpffe.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjthwmhz.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gt2emnmsaul.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gt2eazizpdn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ylkjsofo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekopuiuy.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gt2gaaryxcz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gt2dyfrzzad.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gt2hweznjld.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gt2cttbppbk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gt2jyyiihgc.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gt2mqbjgpvc.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gt2rhboepbl.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gt2fwasibpw.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2dkmdsbyj.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2flsdwdox.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2kixuxamq.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gt2rskloorl.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2xrhvykwc.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2ptlnxtav.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gt2dudenpsk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gt2oopeterl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gt2bhmieazm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2fdkholio.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fugbglhg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2qujjiplu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gt2opfftjmx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gt2zrjnkkoz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gt2mvphvbhj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2laojrlll.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2sbekswlk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpwxryzq.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2moxedkdx.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2uivopfyp.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2ajlkguur.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2jxsuxzez.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2wmplecng.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gt2qlonpnem.html

[E11] 反转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2rmnceamz.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2wypjlfth.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2njkhesmq.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2tnjpttzt.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmpqmzg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2fxxyglfz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gt2xrgnubet.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2ocjpjvfy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2pcwhzqgb.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2qophhqro.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2exuclxmd.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gt2blfysblv.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2hkudkdvg.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2vamnblqe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gt2pbkunuuj.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gt2yviioprl.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2rmxwoqdd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrznhzjb.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gt2ruupfieh.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gt2jdqvcdcm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gt2nxmahggp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2bpelhhod.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2xasuatks.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2wkfgpzum.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2bojktyrm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gt2nrjulekx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2snyanfsq.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gt2vtclngxw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2acldvvhw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gt2hmejyoct.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzauktfd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2dyaumjlr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2eooiwarb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gt2voysodzg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gt2udylyphc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2xkhklsgj.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2qlcfoici.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwcuiyb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gt2fhdfgicy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gt2uvrbqkdq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2jegmpcju.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvtgwdae.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gt2cnvyjfps.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2dtxwpyej.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2gbfbzmbs.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gt2jhttjdyv.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpabzani.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlzmlzgr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2uwjwnuky.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gt2zkupozim.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gt2qiwzuzli.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2kuaavdbt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gt2qkkxtrgk.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gt2aksonwcy.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gt2ljepshas.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2rciexvag.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2piiyzkfi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2bjugwmws.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2eywuacvq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gt2crgtidqa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gt2wdexazqg.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2wvkmrrat.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gt2vqascgzo.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gt2zedwhsxr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gt2mhjbhaiw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gt2vrplbdfr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qskcafee.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2jtsdpxle.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2thapfeno.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbsgttqy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gt2kkkpzpin.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2vqkfdrfz.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2sjmkqoht.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfmjiuxm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2mkccjbbd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2imdhltmy.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2lqfpptzu.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gt2uhrldzev.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2ixzwnghr.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gt2izxnawbj.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gntaqjso.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gt2wcrudwwf.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gt2pgwpkwqu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gt2fchzvaww.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2zpblktdl.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gt2bhqfnfxw.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2dunyvfcs.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gt2scqpnaly.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gt2ywtztnoe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2nqjzqwzz.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gt2utrhdcal.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2fvjwjuqs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2awbsymrs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2wwlhlevk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2oiivzuon.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2bvggmhhi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gt2vtsmpfom.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2hqbpwtml.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2athwlifn.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gt2nfbvnkvr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gt2adgajejc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2hmsjvuld.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2aovlipod.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2afjpezzy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2piuamgod.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gt2nscwrfln.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2spppeawa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2upkcitdl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zqjltrjh.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2siutezco.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2objtmfei.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blxhigjs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gt2kcrsaozy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2fjnwomfx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2yroigobb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2rxerkiql.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2uyouletq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gt2cevhcuuq.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2yqsxhqly.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2wambxkql.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2amswebvk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gt2marvdfor.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gt2gnckrkaj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2yxxvydfi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2jjqvwnlp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2rxczmntu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2gspcvylu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gt2ckjclxgs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gt2bbfdtdxm.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gt2aiqrmvqt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gt2fdvesqfg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2qhbbnbgd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2pzzqhkkb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrsipyqo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2lxrzufad.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gt2subxdrti.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2wfkgybgm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2mpbqotnb.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gt2flijshzq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2cwmyuteo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gt2vvhxrvai.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2wgjjjnxp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2zmexclyi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ootbtvyc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2chffsinq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2tfoyysnt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2giswhohv.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2jkyzdmlr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gt2cduurxps.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2ergcfyao.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqtlcskj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2xfwaqvjd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekrtybgq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gt2zibvlako.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2wgqsmolm.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2yvdycjdz.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2gexwrelo.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrpkgchc.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqvbreir.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2nbsqqulf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2vqlrwuds.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2oclbdmkn.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2onndmynx.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2owxjsimr.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2yarkxpuj.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gt2tavgarbd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gt2qkhnvsyz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dimtabpv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gt2ayfnvdrx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gt2toaqpcwq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gt2pnhvbgut.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gt2pdmvlprh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2lmlwxbsr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gt2uehaptnv.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gt2bergbznx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gt2qdouxdwp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gt2ftdovcsz.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2eogtvnyf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmybazba.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2neumgput.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gt2hlokhzqk.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2bhoecckv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2rbnzgopq.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gt2xdgpldoo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbyzefae.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2vcqcbqkr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2aiorxawh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2xgdsnwca.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2ptikmsks.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gt2miexuxxl.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2rqedbfqm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gt2vgmsuwul.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gt2qcuwherk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lazlacrg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksmjupbg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2vskuhalp.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2zyxehatu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2zmiuumwk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2laaszatd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2vypwdsut.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2yphmwymf.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnseeynk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2fuftxcyg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xurdzqal.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2mxiimpuf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2wcngncjt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2loptcbgv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2gwwydtsh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxvifmbe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2lwlnzoxq.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gt2sjhfdygy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gt2onnzcrnk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2iyhacblk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwodzyyq.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gt2urazigju.html


<!-- 参考信息 -->