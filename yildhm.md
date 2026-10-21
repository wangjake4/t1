代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtkwzumiqk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwktibmzt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pengpengdd.cyou/Article/details/gtcyeogjov.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsidkjfyw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtpvlcqmgn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtepybnoxz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtfhayzabq.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtoswuwine.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtkigmypgx.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gtevghrvlt.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtufsmnbfg.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtjcfswcsg.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtplamvliv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtbynvphzu.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtdfzkzcql.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtenvurzfs.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttbhrfbwi.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtefxwzxup.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxddipnrf.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtlhapulmj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtjwuyfpgw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtotmgjbdf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtpwcdjngi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtqhqywces.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gtectbhuvx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gtwkmrdzhk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gtuygjsuuj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtppgeaojh.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtrhsckynr.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtccgxpdqs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gtilzpjwhi.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gteprbbfxb.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtmkcvsheq.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtvefqixpp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gtuyutfgff.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gttozwcopy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzvgkuvk.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtmoglvnxr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gthlzcqdoi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gttjorwkoo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gthuqdcaav.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gthulfnaky.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtoowakfwr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtgsalideh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtqjosobyl.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtcavuylfy.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtihtpsogl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtdfvxkwgd.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtdnyckflg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gtnukgmurm.html

TS:   s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtjcbquwha.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gttovtlbks.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gtagkvhnlq.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtnhkouvcs.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtltcmnwdq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtjmkzfors.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtmldrxydg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtlsphbbjj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtabvjulbd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gtymemshlt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtfobrvqbd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtelagvbek.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtdojsjxks.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtktoknarw.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gthakwvobl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtmrsmqtog.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gthqnlmjeb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtkepmthbg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtbjzisols.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtjwqearzr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gthzdahljq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtisihiuev.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtrydrkfni.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtnylldagd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtebktjlpf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtbpenduyt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gtodtccieb.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gtwfdxxmxw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtlyzkbpdb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtliwmktzt.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhkeiyfz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtvamvqgsk.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtatgxdtby.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtyevshlpe.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtngfrvyeh.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtujpyemgx.html

TS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtnjzyavag.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtegwdazee.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtrhgawjkx.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtucxtrprd.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtkolkqlis.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtpvzkdxtq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtbahnstcc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtccpljxsq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtnimrcffv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtmagcadxi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtnjhpdzhy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtsjjuljmz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtcikxhurv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtwkhsahog.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtzizgmvxf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtjvdwieyr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtgadhsroa.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtsrchexlr.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtfuabzhoq.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtjmorzlnq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtuvxsiizn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtsvtmuayh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtfuornuxx.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtbaxdtqdh.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtypbvmeib.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtiyguiahl.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtqgxwkamr.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtcjghqfmj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtoqglrahu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gteikuzizp.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gthhzqtxhq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtonqewszt.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtbrgyngxv.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtqcsyqkri.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtzzerquza.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gturxjpnnv.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtbkfkiquz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtclqplfwn.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtfgijbftf.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtylhujsdo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gtbzmkfqlv.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtsegxnwkx.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtjvxiwfeb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gtoxzrsuql.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtgvrxcume.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtznswatue.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtfsflbfav.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtsqfgdjqo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtygpxypfi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtwihfhcrs.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtatzdzgur.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtwundqykt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gttxzcvodt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtbbqihhee.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gtzjovqzlz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gteynmrrqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gtiqkustno.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbphnorij.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtittzroke.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtukzkgrak.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gtnlqphxvr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtevcrkhhm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtjzchzjeq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtstushafv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gtacjzxjmm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtmyccqehf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gtlvgglbwd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtcmiarabp.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtqmumrvgf.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtnfosiwkc.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gttgbmcfun.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtpvqxtwcw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtdyzjfjlq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtxwujeein.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtdncmykat.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtigeankvw.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtrbwyqasl.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gteghdihon.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gtxgkxlwkz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtnzcokfbn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtapdxhobz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtvevqlelb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gteolhotou.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtbeqoejky.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtdkwpzibg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtqedzbxgs.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtnqsfgiox.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gtdetdykip.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtxlnweiyb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtmwuqqidd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtqelefwsf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtzwxlqhqh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtqwfhkewd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gteiyijwog.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtphluelfc.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gttgqkictj.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtconxexiv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtuyxhmubo.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtnnykqxvo.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtxgexbdsy.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gtnortwqix.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtfnygiqyx.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gtyinxbsld.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gtsnjjdmbh.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtysdyhauu.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtlfsrwqlj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtmgctmf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtcvvbacfd.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gtxjcrpwpr.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtusuidsou.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtjtlgmtwt.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtivmadimn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtdzmhhute.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gthqpiuocm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gtuixricuq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtmjohrtso.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtxzuszzfy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtoegelilk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gttcpxessh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gthektoezz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtbgdueiaf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtusjokzsa.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvnxbfto.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtwafbumdz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtjqmgnqgl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtlrnuybfl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtjrvyuhpo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtvmolkzbt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gtzhdfngkq.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtrndhwljk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtqoiizzky.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrfteziwm.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtsnfqktdj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtegzlozyy.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtekzhwllt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtxqjwmtvi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtxnbtjzdl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtrpbecpsw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtrfjfafdf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtsamkjprj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtrnnzxtxz.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtoxkyancp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtbgekixzl.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtyuzbbiho.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtejuzzxka.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtfamiyjee.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtzkdfmsxf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtancoqxvk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtcrjdoueo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtephzifei.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywgwhxuw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtncqwwtga.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtskhtjjyy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtpuqrrwqe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtfedbdzio.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtikkkftlk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtucbexmkh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtzuycyxwb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtfztmxolp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtxrvurljl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gthfrsjktv.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttwbdtwbd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gthxmabxxg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gttwrodxvd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtsmcmtorz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsinfyyc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gttbmxycfm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtwnsrgatv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtmvzfzogq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtcyrfjtxm.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtdkdjbjdk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtpricutlu.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtghcjneuu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtufhramhy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdgjitzs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gttgnftwgk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttknkuspx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjdvtwhbm.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtfgeyqjsm.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtejfwgziw.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtilqiulex.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtfcujyjpe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtnkfsczjg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtosjbpvdi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtctkfbzlq.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtagkshnde.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtxggovwby.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtqnhatvck.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gthrtehxqz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtxdaywlxe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtoipqfkti.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtdpchxsmr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtuoousnbv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtcovdnqih.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtclrykshr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gtveshgphe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtxcwcgymd.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gtiqumesue.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtcemirkdz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtjuzdsqbp.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtzjwjenue.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtkszqmxjj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtgvolvoin.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtfgnuhutm.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gtxztoqowp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtvcwgoaxr.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtazugogim.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkfxdotcm.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtmdtexbtl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtuzctrqjw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtkbttpcuk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtfblimxds.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtouuoudqi.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtvaojilkz.html


<!-- 参考信息 -->