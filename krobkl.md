代发 wailian999

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gthhcxlgfc.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtaynftixm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtnfikwkew.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtfhjityrr.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtcqpvoctc.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtjebwngzi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtiqpcjwrl.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzjxgiwd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtioqqsmyl.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoautxlr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkidierx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtukghraly.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtxibezvhe.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtfcxrvvho.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtgvcqxxsh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtinhpnsvb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gtelnzeaip.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtrhuplhlk.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtpgkfrxpl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtkdjzmjel.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gtwsxqlwho.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtprjrfkto.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtploftvbw.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtfbuqteuo.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtzfkcxiqf.html

Ruby: s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtflxncwnu.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtvazlolja.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtmqlbejdc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtestzegbb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtdnquwsuv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtncgiwkkb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gtsbyasfgc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtwstfwjvh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gttdsbqkaq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtxufwctsz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtzsdxjcjw.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtzqgmynge.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtfesjpioh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtfqtjnfzv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppatfeww.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtxpfpvkgo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtvfifbyhd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtukdwrxmo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtqxpxupsm.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtgvhdsmxv.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtvmnsbyql.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gtozrppdic.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtgwnfqhkv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclzoegay.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtybhdxarv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gtvggzbbml.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtasgdwqnw.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtizvxvkty.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtgoldwfpq.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtetshcimc.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtilwatpep.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gteybckpmj.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtnbckcydn.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtnovtmrwy.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtrjykejlq.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gtjqqgnend.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtakhidpdu.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtqlispwjg.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtkuiiwatj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtqocqzwqc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjthnsma.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtclqdgiwk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtvenfaatm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtnymiipsv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gtgalxibze.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gtduekebyt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtpuzvrjjp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtltdgvbkd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtdrlpjjmh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gtbfiwrfme.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gttzqrhelu.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtgyxowkzq.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtpijoysuk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtcephrsjz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtmosblqut.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtawodimxj.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gtxcklgdog.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtnswzftzr.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtspchyshs.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtpbbmzzfx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gttzqjcaso.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvytlhvqy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtyqxismwp.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqybnlnqc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojmcjvct.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtcbsvbwxr.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtlslyugoj.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtqivdjion.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtyxzsuojl.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gthrncdwrm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtjcqabhho.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtnjbgkqgg.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtqbwhlwbi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkviwupou.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtujgjngdu.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtaxqxsoka.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gtcgenclsq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtcugjytsc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtwejisdaj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtwcgcpggg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gtbspnlyry.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtlzvirlab.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtkzxvddfe.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gttflrttcn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtilsvmxak.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtdhlkttoh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhtkifpx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtalbuwmic.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtsuhykbqr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaouztpe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtprquegds.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gtxqzrmbud.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtnylejirs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gtfxheeeco.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtamatutef.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbiuffly.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gtyaumclhp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtzansfqzg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtswabcqpa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtovekjfve.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gttazlczce.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtqkxskugm.html

Py:   f"{1234567:,}"
来源：http://dali.fengsongda.top/Article/details/gtjlknvakb.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtwmwxghsj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtkyjnhikj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtlsfzlmyh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtwfaiwwnn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtoxfmlhgh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtbmcccluj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtfmxzxncx.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtkbexwbzp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtyiyixxmj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gtmongbwag.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtushurawk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtdwajyjym.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjggryay.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtpjgarzoz.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtharjqcjg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtnmwdqbro.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtdhohhqxu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gteluxtuis.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtpaohyphm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtfcpkeonl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtmzjnbzuv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtlsxtqhyf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtgjuthsgt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtbqyzrtgd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtsdplqgcz.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtiaxebfej.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtqpfslsry.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtftslcpyh.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gttcqeytol.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtkhmuplff.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtahbfczdy.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtxvmvrptq.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtuzaoaciv.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtvnofgqnf.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtbbffcmod.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtuvcoapjy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gttdpcfjjf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmegbzulj.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtqogyxdls.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtjzfquepd.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsybwnhsg.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gtiluwganf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gteqcmmels.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtexxbhnkb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtoferdfto.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtbjuvevwc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtnsyuyhsp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gteehhcifr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtarwwivur.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtyhsxbhub.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtgqnhnypt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtklpiffzk.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtznykckss.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtonyuqkxv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtxneghrtg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtxpvyvndy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtfmwypoiz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtontomhyy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gtlaqvxupe.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtrtqnxgsl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtggqfjsin.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtotoluvjc.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtbhzebnec.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsiiykolf.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtjazcilvs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtheebgeax.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjancqdwo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtqcdwzyrg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtydzgpdnx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtaejeqqip.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtozttoasg.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtarwwezbx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtyaglupcg.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtbhxhbaoz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtutsbveda.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gtxezjruqx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtlkkhuwhi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gthhssvukm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtpaqgbsnr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtuijpvjbn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtmofxnhxs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtscwrdevd.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtqhkdpcau.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtqcjtudgg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtpvehuovj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtmnvsttxq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtpnwcijdx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gttwerclig.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gtlnlaqoph.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtohgvmwem.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gthozertfy.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzdbifjo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtsmnzypdj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtbgtbujcl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtwjrctfcc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtagofetiv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtdziealgg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtqcjgdkir.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtpkxqzkuw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtioyxukxb.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtogvudgor.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gtsgcbfnbm.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtmrokhbpg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtsptscpxu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagcysrgs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtrummbdbp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtljvcauml.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtborvtasi.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtkfltmevw.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtupdomlpu.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgwhjawjl.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtkyjbftci.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtzzylxemr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtennmhpfe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtauqujvpi.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtokmsnrna.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtsylychvg.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtzpzyovkb.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gthtjbnloe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gturbfhezq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtwvwceptv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtsxnwhcjs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtjherthik.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtgtfwbvzq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gtfirdfdfo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmhbbuig.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtsvehbnne.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtpboadqxo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtzgjursck.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gttuxkmdib.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtqkuevuot.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtgbyxpnxe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtnbdrtusl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpyyixyl.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtteiekaph.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtnvsvxphh.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtdwbfcujb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvgjngeex.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtvyrdvxvt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gthdmuvqcn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtzyyrgfqt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtajnfzbnt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtzltegrtz.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtopghgvex.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtznwgcvtb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtrfwplkng.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjmoxcbyv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtzqgttcny.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpyizglja.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gtdyrzxndm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtfnqspwgk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqnkginzl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtxfkojask.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtbznhxggi.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzdckkbp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtcdrlgmhq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gthmgmxcvw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtveepusfa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbxqhadml.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gtpqbxvvhz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtiksgiyfi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtpthgczrf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtwjgsbbbg.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtogwcdsdk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtkrtstpmt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtfyjeugdd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtzrtlrmtw.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtmibokraf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtjqucrcoy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtpdbzeomb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtrzfehwpw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtjzyrzwdb.html


<!-- 参考信息 -->