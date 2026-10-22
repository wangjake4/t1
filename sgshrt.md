代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gtepiyrwyz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtmnhisbsz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtnslhyckj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtwtvrauvl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtqidanerw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gteuxkxsmh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gteppvlllq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtwijryzub.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtassnvmga.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvojvvna.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gttgtcxepu.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gthdupbqzc.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtmemhhuhb.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtgxwtrkyr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gtuxkgnrly.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtkwdanvjq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gteeeemcgo.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtgwdgcfko.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gtuynyjqrq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtrzeyqjoi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtyvqytucj.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtwbjcpqcz.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtjotdnyci.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gthzjoosyx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gtxrexcrkr.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gtgowssqfs.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gtbrnwjjit.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtybmltjjo.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtampxgxba.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtqnnxxiqn.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtswfdsuto.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gttyyfoyes.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gtyvdicuni.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gtrrumafrh.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtloxcnmog.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtrqjowhkx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gterqfwteb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtytcocomi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelsotqzm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtzkwfefym.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gteiycgnel.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtfldiekpy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtvhzqcgie.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gtfitbrthe.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtxqelsiyy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtqwmtluzr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtglirywls.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtuwxsjnyu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtgfikhhjs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtzirrkexc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtznfvrfco.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gteaeaurcq.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtriyiwqpr.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gtrkxvtwzm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtkfuridnl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gturynmpgi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gtcktxnbrc.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtdtfrdaoj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuutstuc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzdgzabea.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gttkbwlhgj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwjehlgz.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gtnulpmqgl.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gtzfhxalve.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtplfmltly.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtkrwgsnud.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtdmkbneao.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtansbhzum.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gtecjkkjbq.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtuyjaijra.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtlpefrkip.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gtfonxnyms.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtvmishxvk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtagshtwxx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtqxyfnjto.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtifkjusam.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtzjazqwmo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gtocmtpifr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtizxdjklp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtjqqqsnhy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtuxbintvb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gtlzfksdbx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gtyiqxliil.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtsnbablaa.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtqzkmckdz.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtmsybaqxe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gttplwyxfo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtrvwzapyu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtzddkkbgf.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtzozhabgg.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtarsrfnnl.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtezzrmpzr.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtkftqhupf.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtzkniatcd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtgksygzce.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gttfygzazi.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtnumybdoe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtdptyqogu.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtmgbvkxno.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtefqiccyf.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtpxpvgssu.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtuihxwufa.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtphnbjbcv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gtqvmydjvn.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtgaqgaryl.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtkzydmwzf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gtjiotygwk.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtedfdgulh.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtyhqrrlbl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtfrwdttiw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtjpvspuwz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gthisxmjei.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtkavoadjm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtrhvmwmlm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtpdqafeyg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtsdmpmedt.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtmihxqbur.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtfckfgoza.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtawutyptc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcavqalak.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtldrbmccg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtnlrkzteu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtobxbkyxv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gtmrjjqmgw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtpahqhjiz.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtsovqbnsw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtmjyrozee.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtrhkscyhg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtwagtpfpf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtjfeybobp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtdnglanvl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtfnmvtcft.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmdbrqbti.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtpmckejrn.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtwbwspyzh.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtrukczodf.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtkczjmrly.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtjpgjoiso.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtneyaefyn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtjjzrycap.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gtkaqitdyk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtdekbzkvr.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtckhhhavy.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtlltsedto.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtijqjuxjd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gtevdeymjt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtcihsnblh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtfqgiepzf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtqdbcioox.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtgtrzroqa.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtserlhfhm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtamaccfjx.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtvrokqyto.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtyumbgyzl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtvwatxzzi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtclhuaeyr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwywajjbx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gthrgbzipq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymelxvpj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtfkgeiwst.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtgfrhrmli.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtgljoavwe.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtlqujrtux.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtsstqozhx.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtlgutemxx.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtiarradpx.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtadrqpdls.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtxxrztklx.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtlegmgshe.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtoaltuvmb.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtusmgumpi.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtbeihkmbp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtpaocozdl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtbpnjpuxt.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbrzsdma.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtzgedveyv.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gteaghidap.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtdpkbxpct.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtugeoeaaa.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gtauveoxsz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gterapjjlw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtqpscvunq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtvbirstmc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtiqojlblq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtlkshjqiw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtzdnqgddk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtagiviivx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtgqmcfcga.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtczgcells.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gtofnftwmn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtbjweehye.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtntjzhzse.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtlgjaxtnm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gthpufkrpg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gtyujhskwm.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtjxzewnos.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gttamsjvzb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgumuthzt.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtbutgxzqk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlwqmybiv.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtiwqnviac.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtvjpnuezr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtpvktxngd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtxrfabipx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtoblmhvdj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtmoyxeawk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtjixqtmdh.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthdtoolnu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtlvngaclo.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtcbjuwvox.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtgaskycml.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtysqkijpt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtnrjxrdgl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtyrzfwndm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtkrqzdxag.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtzemkwnwt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndcmnxqx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtefxzukfk.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtqnwdfeie.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtyxaytjzz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzospsjxb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtcbcygsvc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtajefvcwy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajvugzrm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtrqloaqji.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtfykavtav.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtpemcwqig.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gtzozspcir.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gthzxgvdvq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtoktwewor.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtufwzhmxq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtgsknyzdg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtedfjbyks.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtlynlbjlp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtlaupmlwb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtguhrjslo.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtrvmccrvt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gttwibwgjy.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtudzcpcgr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttuiyrrcg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtaxxxmlhw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtvvbcmcdn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbukhokit.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkiftoit.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdjfiijgx.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtrrmvihte.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtskvazaru.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgecwwcyy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsslktmfq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvsbwxwey.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtzknvelkz.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtgiuytfas.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtyjvrvkgz.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtofconwfo.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtwqlyxkni.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtjsgzhbcr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gthajeozeu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtrpgajlhw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gttxhjgitm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtrrtoaqhd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtlrnnmsul.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtwtptvtuz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtfzoyulzb.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtajmcofar.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtqwmdxumq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrzfktgr.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtynesjkvi.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtsxykpqkw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtawznnpkh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gtyhvccjyf.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtqhxlktfi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtrdxorvif.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gttxpuqcmf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjquxmfpd.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtlmrmgnrw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtcjxwbdbg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtpvcmttod.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtcojdotms.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtemhqsbes.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqwxwyjp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gtoqcehjcs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtcptlrczb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfnyqtuwa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtdawjqxkj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtpgtlxkol.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqhuxfqnr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtdobkygjc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpjpgbwvg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfevtbyki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gttpppumjj.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtlmayueep.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtslhfodvh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtcbzhgbzp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtaqfbnwxb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtfunujsde.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtspdxrwpu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtmzkvzpcb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkbccivgu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtutebhmms.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtpwitffiq.html


<!-- 参考信息 -->