代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gtzkqpdeit.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrosslaw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtgvaapste.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtnbvivpgl.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtzsguirlv.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtemxqhjuf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gtdwqstfuf.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtoxbozgjl.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtvwfbumsy.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtaeeuumfh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gtoytkrizd.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtovxtxckt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gtjqytrdew.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtjhmormus.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeysadph.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtoolepsmk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtjqrphpxp.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoeuixug.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtkcutbopm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtizudbtrg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtaopzvvby.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gtmkzpzoph.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtuzkenqzm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtjbqfcomw.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gtirciqkmv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtmsfsdoxn.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtiujuesaa.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtzqxmijik.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtjupnkdto.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gtgtjzacdo.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtzvqlkspe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gtjyuzwlax.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtpdhntglt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtdbdiajfm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gttnqctipv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gtpwoyaavz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtchplvpfb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtpahoulku.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gtmkbjvyze.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtwgijumaf.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gtwtgbyduo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtnwxiqcpe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtwcjelcfc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtlcvcrhft.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtidlfwvta.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtteuqlrlx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtdblllekb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gttexzfwjl.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gteuaqvxgl.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtewuxewgq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdgbtmrw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtdnrhoxdu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gtxscdwbzi.html

TS:   s.split(",")
来源：http://dali.shzxlz.cn/Article/details/gtsyepmyou.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtrncjbloe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gtomayxsex.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gtfjvdtpex.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gtrjmuhpty.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gtvbqlsllr.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtzpxviadr.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtsxeixxch.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtjwsfansr.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gthkrdeata.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtbbwkhznp.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtpeosyebc.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshmujsnr.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtufvixnii.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtazxkvuho.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzoqehzfw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtnuxtzyhs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtpcknffqj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtwzkeobqr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtsxyjnfew.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwqkosmh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtzxjbvprl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtrwaexgci.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gtsvahxzqv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtqmaglnrt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtuumufvtr.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtqaahwdps.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtpuxboeen.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtbfuxadlu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtxztnvmfc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtwvfuwyal.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtrclhhoiw.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtkeoswpgh.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtwylpqgpv.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtzlxeyqff.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtrvjiwkxe.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmolalxd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtroygsjof.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtokoyegqt.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtcxfpsimj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtwtuzqgej.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtleqbfdnp.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtuceilpat.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtiqmyweta.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtugfdxsad.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtohgksuxq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtonhcrwmo.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gthagahkdj.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtqmjzinny.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhgkmxcf.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtyxddqocf.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gteecfbkhf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtyvpnldeu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtgjcrrvqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtmxfcgqkf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtktowzeja.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtrduxehon.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtzojzsava.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gtmamtgubj.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtvgnqqjjf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtsviseemn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuumtheg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtwxcxatwu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gtvntcihgp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtlrgtslde.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtkxcjsqdc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtvpyrmppq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtyfehfmhq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtnggpxfef.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtegakratx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfnyxyzb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtyitfvyvv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtrgoqpnca.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtezkphpmu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtchdvhfee.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtgiuitzbx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtgeutirlb.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtnbgcpitw.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtxinnmjjk.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtclllqgdr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtzdpsuuoj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtzchjoypm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gthsmmqcxr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtltmmnize.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtrvolhfma.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtmhxgeipw.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtgliimlfo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gttxsfohfb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gteypeuezj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtynjrwise.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtuazwbsel.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtkhlwamec.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtwkpqpprr.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtmrqdxceu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtwummteqw.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtfaxlhwnl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gtdbbnbclz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtnxiuruqt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtfnerpblt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtjgkknvba.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtopjzbciq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtvumsnkjs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtlcikgapd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtetmyjtzz.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtybdhvtir.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtcfhmgjac.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtrkzgkanl.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtcggqbfwn.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gttkrforwv.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gteeopoduq.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtnxtlfpkh.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gtqbnsuxhw.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtfevoeitc.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gttjffyfmm.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtduygznsa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtluwjqvra.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirhyorgx.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gtvagzsxoj.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtpszwulng.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtmhrijitj.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtygzdzzit.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzphpgxuu.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gtdyphstfc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtuswnavkc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtklxfdggz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtzkvqhsxx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtperwkpcf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtuffubkej.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gtashbebgq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtapipbxer.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gthqzxovsi.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtwfhxkhnc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtepgbkodq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtzofkmtmk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtxpfdalhu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtnjqrmbof.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtprxgkjfd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtmbuhycch.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtxdxhdpwz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtauwshmgg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpndkdntx.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtamiqblav.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwnoerdkw.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gteatrbksa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gtblphkusd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtehnhbnsy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtfvfsbzfa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoiglrro.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtivmrixzs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtaeccskre.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtewrlcahb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gtehudrrjv.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtxgcgjdbp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gteqilzira.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtftgdyces.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtdjcqtvtm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtsihntwcf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtwksfcvms.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdzzvsnp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gttiyyomfu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtjpluiilf.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtwfpujxrs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gttvhgiwuf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtvkhvamlr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtwkcooaxh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtyvqkzyhb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtgwzfdooz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gtfzdwrbup.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gtefluckok.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtbrwwmejs.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtgosxcoip.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gtcjtgxwga.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtiorvorxb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtnjzlyqzd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gttkbmxazt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtmvykrsmb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtqhgpxltg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtnbdipkuc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtpdbatzkr.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtvyjsiaxe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtfdicfgxp.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtgfbkpcio.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtfxnewxel.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwjijhpvg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtohgamfvn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtbldauqpl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqqwubulu.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtrciszxhn.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtmqmeviko.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtnfhbpcts.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtcqbvyunu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqxjkplai.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpgfmllc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtnpdbsxhs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtorjbxpbi.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtfmkgijsv.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtadqdlsuf.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gthotvvceg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtvotlcvqm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtphcjomel.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmtnjpiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gttfxjvmpy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtmuonmktt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtjfslkpre.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtqkpwwgaa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtlabutyqj.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtvjxfyiwm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gtpasqfivg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtomccuumy.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtqvbegbxj.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gteqtpscpq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtfbcwhfvh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gtlrbuqpke.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gtcwzvjwew.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gtztbueopr.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtullhrdze.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtizqyzstb.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtubchxjft.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtvuopsmaw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtbgrwtyth.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtozlyuybg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtojkyeqfn.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtmhigmcis.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtrcgdvped.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtmxtxfykv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gttzdrqlql.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtusismyiu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtrdgccucl.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtukogfmrs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtijizcsjj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtemhpnyyr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtldpjtrym.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoxbiavn.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtitjyaqej.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjfiartbp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gtbbcgqleb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtnuedaczm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gterdaaagx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtovewplxs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gtxlgjoahi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gthstmbugh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtlhcccizo.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtjirbpmmo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gteeysznsd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gtqgnqeesc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gttvyigkoy.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtmrcztfsp.html


<!-- 参考信息 -->