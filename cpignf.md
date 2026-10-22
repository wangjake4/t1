代发 wailian999

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtkwluehnd.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvihehwmc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gtgztelkfa.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gttgphqxws.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtjovgborz.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtnzcgytew.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtvvlqgnhs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtzfqlhdau.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtrhxzdufw.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcthotuy.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtwzkzkbzk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtwpmwxyks.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtjiplswzw.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtlrnlkoew.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gthtfqoabf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtfdrldpes.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtvnxtjddz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtatlejcaa.html

TS:   s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtoxqpezhq.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtedruvmmx.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtermddesg.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtoucbysat.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtaoetxjfw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zycfv.cn/Article/details/gthqqgrcze.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gtgdansxgv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzkpmqeo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtojqxhkjj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gtqywvboie.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtshlsakyh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtencivlno.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gtejgzzztr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtclaxdgvp.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtxpwxilgd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gttmahxlxm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtyjmjtagy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtdawfpkbe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtyftwbxiw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtiknklxju.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtdxuejjem.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtphwegawb.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtyfpjdgzq.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtxcladrmi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtgwkzdtkz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtoiulbxxj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtljrxymnl.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtnhqzfhwo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtbzllchyk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gtowdedsob.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtwhwmyaeo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaswzngoe.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtenoqtbqy.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtsfmdwzaw.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtqmahossl.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtysswqphm.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtddhokehs.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gtikuzaieb.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtrulhpwzv.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtneiobplz.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtilnajfdb.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtbslkvnns.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptipmsce.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyzpxabi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtcavbmmxf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtzntsigwt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gtfvtatper.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtuxjbzgbd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gtrcsqtijr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtcgtjcqhf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtqjrajwof.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtrugevamw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtlmccvoiw.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtekbshzcv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtrawekcwk.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnondxikj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtqnfoenjy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gthkzfdjto.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gtzcftoano.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtfukhqqgf.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtqcftpndc.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtatytddfx.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtaybletkk.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtxfcwfqvy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtkvhkjpwy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjfpsdle.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtcgtuutoi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtiyadpgas.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtexcvcyel.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtcwyrbyzf.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gtccctbfth.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtpfpzgccl.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtzebrbnur.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoweibigw.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtybytnpjx.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtvlyduysc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gtgtrapinl.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtphltzwtf.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtpcqjxnko.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gthonvefqx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtvrupaatl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtonliimlr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtmofczvci.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gtdhtzqvya.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtxekscusg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtnhyvqnmu.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtczbievwf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gtceiclnmn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxzeqqpe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtefgznawq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gtxuhvboac.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gtizuebhns.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtpvvbxpbl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtowpyswyt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuzcmnfa.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtiubkjcbl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbdzneixb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtrxioyyzu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtoiyzqeyt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtohdeflhi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtjtmsvltk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtfakputee.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgwrsmsa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrtjlqgy.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtvquwsdxk.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfbnpthm.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gttnfmzxqm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtjcshkrya.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtiavyyyof.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuqtvdzs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gtfwjtdgyt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtjdiibelh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtdjpwiknr.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gtcnbwqxup.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtxgnpdaqd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtjipmzwbs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjnlbgmho.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtuwkvufet.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtniwbygeg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtcmhzlljb.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtbvokiwro.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtbwnrpetf.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtwlspraaf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gtybcjetey.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtkdhsdoqi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtrfrhfwav.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtaxbpbith.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtodhvnfvk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtdfqankuy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtsxdnkeqz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtxiojtxuh.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtrhwlxvfz.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtrfutobjt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtplvlxzxc.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gttzxwweea.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtkswliwxx.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsmpjbmm.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbdkcrdn.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtjwijjaih.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtealklmcp.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gtgerjhcxb.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtjyqgkopm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gthpoqjutg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtexlcjlbk.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtwspswyvd.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtzajoeqfh.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtrgpzbitb.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdpwmkhi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjosntkvg.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtdhrjwcwt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtfandsrdp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtcvssnofc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtjhlwmyec.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gthfujjcmh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtdjxpanpg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtlryodoiz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtoylflaba.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtxilhonrw.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtmgdtmrxo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtajxrqsjf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtgpludwft.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtqtlgppid.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtiykdzaly.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtctnpssnb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gtfxjuisfi.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtjrmelubl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtcgimewxy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbteyretj.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtvmjhtwvv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvjbsbnzg.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtqnsxccbo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtvntjgour.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtxshzkggf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtnjdxcits.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtmpnlquzk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtalxmpelx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtupagsfxr.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtunpqvjen.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gterszhvsk.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gtduepjers.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtvilglchd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfvewqacx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtiatfkmru.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtpigdlsqb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtokuinriv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtzllrdksq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtyjbcdpuz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gttmmlqvnc.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtjqtpxscq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtjjkomppd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvkbixvu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtybatcsgp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtquyjwlnr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gtkvvvovdr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtyfxsuvkl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtsvhgravj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtgjsqesqx.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtfyjhifoi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtofvgmjnl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtpfnrwbzi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtlpvfbtun.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtzrbzqtdm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtiscrvspt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtbdhiemqy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gthpgionaw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtwirebvvt.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gteudtqnsb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtfeyypmcs.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtatkxofmz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtxnravriy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtgrilzwgi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtxozcvmkd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtnvrawnvp.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzgfwthra.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtxdmcljbs.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtcevibpim.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtthcbdkam.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtgwntkdmk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtucyuwbru.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzunkqjtl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtcbjfzjaa.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtepzfwfqi.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtexbcywqu.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtayyvmzcb.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtvsopfmym.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtbssgcnkl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtbtyiolab.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtjleezljy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtagvfkrfl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtnhogxfhz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtkzgghcxw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgaipmdo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtwfjxsngh.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtpxosjfwx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtrlnhfffl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtigbiebqo.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtroorunmt.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtisvuzqzx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtgxtvpfti.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtmmnnicxp.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gthwrssodk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtbaobtktp.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtygbtajib.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtsliakaet.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahbofdup.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtfegkhjzi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtijrzkbfi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtttxybczr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtbxlcnpbw.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwkearmud.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtxvwxbngu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gttmtjjxse.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbopjbqak.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtivlzuoib.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtsfwmandn.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gttlnrqwmb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtxbfjssay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtpssbqflx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgdcbxbwk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwzdwblai.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtrxattuvu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdhtrmesk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtzbczskjy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjejthfhs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtqdpzsjzc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtfwvpuwiv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtssdrjykt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaeykblb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtrnaktulg.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtlsmqdmva.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gttdsistww.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gtesilbtas.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtrchejlbv.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gteqprsgsk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzizqdfif.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtdpunvtlf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtpelposvk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqqwxugx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcbldgcwd.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtjqdmmhah.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtlfuiireh.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtjzoyhnje.html


<!-- 参考信息 -->