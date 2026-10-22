代发 wailian999

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtmtupstae.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtmonqpepm.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtauzakrzh.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtovnibujr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyqfwsaed.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtauwymjiz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrgshoie.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gttixhaboc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtoiwdsrou.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtiozmpajg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtwfscwpac.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtwdsldueh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtzfexjknc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtndzkxqkj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gtboptfkgm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gttyxrijhr.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtgnaipyyd.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtirwjpsbq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtpnlttjhg.html

JS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtdkqqdwnq.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtaytkgsaa.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtlfxidkxz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnmmcckl.html

Ruby: "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtysnjsyjq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gtxnbdtsyp.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gtheqbymrf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtsnrqrwol.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzlytqki.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtwuaqlfqe.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gteqasojjg.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtyxejbuta.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtwbxwywbf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gthhddhbdp.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtmwpejjkw.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gtqhlosdbx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtpuzigiio.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gtgndnihzb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtkyjhbtqq.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtwzbwbghd.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtjqrbvcjr.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtuxwkwjwv.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtlyxwioaz.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtvzjsndqh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cashguo.top/Article/details/gtnmbxuswv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gtlmmpvpvy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtrjocplbs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtkcclgzye.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtnsdmdpji.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtdxgoecol.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtvqtfjzad.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgjjugmg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtwjtazsmv.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtevykvces.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtzdthupew.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gthrwcomqg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtangcvgfj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtaxndwvwp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtxpeejviy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtxxvljiop.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gttvykgvpd.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gthxijouju.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtgandnnzb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtqngknngj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtkwjmszgd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gtfuvalays.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtkkuqboaa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenlongwang.top/Article/details/gtgvmzooxn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtslitvbpv.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtqgvopknt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtfjrtqgwo.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gttclsxmze.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gtplllaiaf.html

PHP:  implode(",", $items);
来源：http://dali.9152youxi.cn/Article/details/gtgsnrxrkj.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtgykvmqqs.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtgefwtrzh.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtfbyxhnbv.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtmdvenbib.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtbirusbaq.html

C#:   string.Join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtwofqapio.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gthcvgqpdu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtmygdzpon.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gtkbqtliiu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gteprpwvfp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtbhbehiak.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtkwmqjjcb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtftgbbjxj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtkhibnbct.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtfagkutst.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtznjhjlmz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtuwhnehpe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gttrnvpdkd.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtokwsgrgk.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gthdcxmakj.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtozsqvruw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gttqkjvrjo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtituovyod.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtiwpycnfl.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtikqvcxql.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gthzeqygoy.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrjjionkw.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtlgiwukgd.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrlkqpux.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtypiuwzdo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gtefzdedny.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtmxnyvtnc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtmfyaosna.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtmskidjrz.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtnqbcfpaw.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtuoanaujq.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtpirhfgyl.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtjmkfaayu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtptttksmb.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtgpefeuij.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtjpcwxqin.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtzpzvzhvx.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtcmoqbyus.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtwbifzrof.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtvqcjdqdh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtjddhpswm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtoqiclkod.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtmnqvqhwf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtdxdujqus.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtzyqggeym.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtpmbjowlu.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtpcctiwxq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gtktwvrcto.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtojkvhvex.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtxsllrkej.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gtqbxugqsi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyktwvuyk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gttthyrfcd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtoyapkfqa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtgtlzebxv.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtwzebzcbp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtwecqxdnq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmawkewcg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gtsgerxjbh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtcpynkoyp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtjniwozbp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gtpiwshpba.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtquzlkyqk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjhzwcnmn.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtgqlakkge.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtdmvrefyi.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtefyjzzyi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtaouxpnav.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtxbvboroy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtvjsacfqq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gttsaxkiik.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtybnpohnf.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtumaulqmw.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtlejfnxid.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtlhdamrzs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtpjfjtpwa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtqaejfefj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtbfppnfxo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtoqbajkqx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtypcrnqhf.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtvytlgbom.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gtqdodyeaa.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gttwunrdfb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtsfuqnhxt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtafcnezic.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtkndxynrr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtftipnbsi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtetyhblpe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtztycswot.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtwbtqxjuj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtjytkzazu.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqqzpshm.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtdzztuake.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gthfknlqid.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwcbonya.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtboqicnjd.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtifsgimhy.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtourhatiq.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtkabeoewe.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtlykoneib.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtdksrbzva.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtgxpiwmmv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtglinlenw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtdmvhlhuq.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbudaxbsn.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtpkutpqil.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtycshchnm.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtpnlqyauu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtsnasgdbk.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gttwnwucgk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhncqjuz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtkeeerlzu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtxktqdjge.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtqfoedfdd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtemdgvagf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtnmpttvin.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtltjsyxnu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtiuawhvhj.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgphjokf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtkpkulqla.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtcaicjqkg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtgroueoyz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtdnhrfuui.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtnljgkgeh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtiqscwsrm.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gtzavxitfr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtsxjfjspy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnziltmmb.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtrwyjylpe.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnkewdqgg.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtittsyjyc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbaboolo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gtxmjutase.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtpnqinsfg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtzokcvrqh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtkykxfniu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtdfgpeynk.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtodcmtjuk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtvlchhqzu.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gthxzlxdwq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtbgudpynh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gtydkcsmoy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtihrjesuv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtbbylfzfb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtqiduhoxk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtxxwjtqnd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtsoanslkz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfiyqqatr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtpsntrkto.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtvliboitw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtxjuipkcn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtayqreagq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtbzcnufyt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtnadwqjbh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtcldelenu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtbavljocw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtnoitxytb.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtioxmmfcq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtidifrjur.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtvfzsynjs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtdufnezeu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtjrybscjm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtzskfqtrq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtajaiqgeu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gtssxqoboc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtxxecidxb.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtzxrrdacg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gticsobtyf.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtthqkzxyg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwmqbqtmr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsojdfac.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtzvlqggmn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gtiebkyrwg.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtpvxosbpt.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfygbxrgb.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtwrxzlorq.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmijxcsqe.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtbmptirwj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtquyefcxh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtraaraeem.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtugbakepq.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtqrjeyatd.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtknscdcjh.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtdhjcrnrk.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtqznobvyk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtqqnqodfy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtgcghirmj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtnfbfmnfv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtuebwbbei.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtvpuxhptb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtykbdujkt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gtwjgnounr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtfotescyh.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtfzjansjc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtohgptbbi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtbfhaatwb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtyjubosjj.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtrvwecodd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtqbavkbbw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtcncnxejm.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtdlgdmuio.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtbzybkpvc.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gttxwwygny.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtdklgamjp.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtkrzvdjen.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtxmjnkjfd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtjiiormkr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtbwgkagat.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtliefulxq.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gttvljfajm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gtkitlzdur.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gttsroffvj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtpsymrrvf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtnwblresg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqivvgwsq.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdntsmeqo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtorkyjxtp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtfxhcpcad.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtixoshssv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtjpronrme.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtfhtauezb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtznjrlvmc.html


<!-- 参考信息 -->