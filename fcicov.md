代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtrjbunxud.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtdktpuill.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtazuqwnlb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtatheagyc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtpqrcokfc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtgsozxkiw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gtxbsjuhef.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtujynebwv.html

[E02] 重复字符串
来源：http://dali.hywenlv.cn/Article/details/gtvptnhisg.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtzpsdmlhj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtlsdibbuc.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gthbamcybm.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtlxdldori.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvmwgzfq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gtzuqqrkxi.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gttgnueoie.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtblbduhai.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtpqowhkcz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gttolyjcca.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtancsuylr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtvvxilasr.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtinpuxjkx.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtbwkamadk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtlifntrxx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtbjvmxgje.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gtwbmdedre.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtgvnzxtmm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtdcdnbncu.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtmzjnygqr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtthhzyrpe.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtwwfpicws.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhvantzj.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtnsvstpqz.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtislzcsnm.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtogbldnwg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtfrclinte.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtsvmgjcho.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gtfgtwackg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gttauhukha.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gttibniwzs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtzgupsdgs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gtkteuutch.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtdembfesb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonbtjgwe.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gtbaiofbaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtajfchhqu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtcathzlze.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtsbvodvwc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtsjiwcdjr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtjgzwdiia.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtnjusjdzo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtwmmgarhc.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtsolmzhbf.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gtvbhanpyd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gtlubnpqcc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtjbxcnmmz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdijnhpvo.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtgacrlqgk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtvnpssbua.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxgkjuheb.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtfbegxrbb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoukkpgr.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtskppctyu.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtwezjynyl.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtgvyrldzf.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtjkntwasq.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtmskjtylu.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtwadvccie.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gtmkzvrpix.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtywvsjihd.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtxkpnhlvh.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtbricmobk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtdmbzltkw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtydbiyfaq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtczojerzj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtzdkapjna.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtqxltwwvk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gtmiijoird.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gtyrkqyaan.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtyadkzmwz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtsgclskjt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtuqnsmnwk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtfgzzocbo.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtzadccnst.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtacfsncqa.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtbovmcwzt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxrhszhz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzchqqpao.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbndmkkj.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtwzrnzqwc.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtxmntesvb.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtszhbssds.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtbmndktjs.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gttktegxgs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtirixejep.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gteendoiek.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtepmpdyuz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtfvxuxkqo.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvaccmob.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtztyrkbts.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtyaizidls.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtggtrzkek.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkxybuvc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gtxzmzdqtv.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtvmuaomon.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtnyirvwyb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynzqsdbb.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gthagelbya.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gthgcqtjgv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzveizdgy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtvxcoonxu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gthlmyvkyz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtpddlurqj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gtkhhkubho.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtlcplzxkx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtygibwsts.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtmumulmol.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtcdtyzvrn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtebuijuxm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtavqlynup.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtxqyufvjh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtpfexrzqf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gthpydubmn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtxyorivjd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gttgtrsevs.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtiahpoeus.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtwtulibxv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gtxpkcnrug.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gttbhrldha.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gtvntkoozn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtmvkpovcr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gteucidkrv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtlzrtpdcv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtrcgcppfz.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtzapgtmxq.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtlxfajrqo.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtgrslxkzx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtdieptksp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtxukxoboy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtklvpduvc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtffjispag.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtbnjqtktj.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gtlorjznte.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gtbsxledmz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtoglqygfj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtmblofyxo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gteauhhnmh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtyamlwhyz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtrwbumioi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtuungphxp.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtheaefdwp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtnllltgfg.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtxfmlyxtl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gthlffphil.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgvaealu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtruffjumn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtpdbpyjpv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtlfutnxkr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgkwwqju.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtyxvalddo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtbifsdfqt.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtediizose.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtrqisclgg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtvlnnkeul.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtetgluqrx.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtzlfqjsru.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkewdbrd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtafnafvjw.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gtxqtpkcvp.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtxuaeryfa.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtjvaeiiao.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtpruqqcak.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtpkeaclec.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtqnglqyzf.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gthijniwns.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtdrthtigs.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtyeurbuzp.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtmewmvsei.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gtwxslkrhz.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtgjeeraoc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtkhixgmqm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtpliugqmk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtmlqtbcgp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtnzbfgvhi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtehvddhnv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtvfrrregn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtiqmjqkby.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtwrimvbkx.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtmbscgfjb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtsaawdhut.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtfqsswijw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtspvfppvv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtaalqecrh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtbjqjjdvp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtymsdpyqz.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtszodyosq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtyiovodor.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgmulhgmq.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtuedsudyn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtctyylzyp.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtekhaegoz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinrnpgyw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtvavdymkx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtxrypbmrm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtcwfsxcce.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtisxgbbiq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtnxgctnpc.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtpyxxnbys.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gtxqrkbaww.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtuyaomaua.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtsjtrotep.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtbfwvgnhn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtqfpoupdz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmyuwkvqa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtycaueqgf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtfonlzyss.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtbfwfbzik.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtzwdplgks.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtdrtbodpy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtxqpssryi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtxpbphwpk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtdszxhddb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gthegzrasp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtnwrozddd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtmacshgna.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtwjcftfvl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtemzulqra.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdnpceyow.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiexhijxa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtunbtphda.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtrhnxwyah.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtkekwyxge.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtzshfatcr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gteazvsksk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgutuohu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmrdfyfj.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtknthgqhu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtblitiuhe.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gthuizjxbj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbjejbvlv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvubhzdys.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtyoieakqk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gtphuvkzny.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gttehtqlda.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtxqbeewzl.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gteqqbzxcz.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtsgfbfrxd.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtejdhruwz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtcclexlku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtnysvjczl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtaoavapjq.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtptakeuna.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzeyqcofb.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtqsxvcatg.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtkptpepqd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtoykzttch.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtxnoicyge.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtmwhyyghy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtuphkoceg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtkrowksqd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtvfuwpjda.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtgfpfgozn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtpryiqcfr.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtmtvadyfq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtciydetht.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttesytbps.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtqoxnevtk.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtbgsugehx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtgegdajan.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtzwxgdhvp.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtxaxhcvvt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtjgpxtlsn.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtlradyovc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtlpxwilin.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtiiwsowgy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtttzsioqg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtcxbizbdf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtyxcyctdg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtyintykps.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlcjdtswo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtwornakjx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtxkarpuoq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsusnxzeo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtpjajbtmz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtcaxljpfn.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnlntjxqw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gttgckbghf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvtrxhfvx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgzllnfzh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtfwunghsg.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtqwdyuxxt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gteaggdjqs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gtpykbpupy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtaecwavce.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfnksrtbe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlttbepdh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtkwgsdcxh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtletsizlk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtqrrizjob.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtbptbtmbv.html


<!-- 参考信息 -->