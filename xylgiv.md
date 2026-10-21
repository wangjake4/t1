代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemhvsgza.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtpeijqmwc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gtghyqbkum.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtegupmbcx.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gtzonpguis.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtdqjwrfcu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtgwralheu.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gthogjordd.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtubflnyvl.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtaycssmxu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtlwkuhbok.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtknbjwcza.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtvcktwkgl.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtgyrxxqmd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gtflkjvbpy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtsdbuvirq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtddyyvuil.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtzrguvrwe.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtaftgeanc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtpgtelgoj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtslasuzar.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtiwxxoiqj.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gtgvadawbp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtfwwjvdqh.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtovwkkjdx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gtslikbfbt.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gthetaafbs.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtaheoriqj.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtwoynwbid.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtusrkoaoy.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gtlehkmmty.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gtmevbclvi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gttpruvbqo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gtxjskkdjo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtcetisusg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gttadlolgt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtnfsuxcxq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gttbprbgvy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtbogfglcn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtcseblhue.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gtbglkyqxg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gthuyiabwv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxzudlxy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtyngfxmnb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtjwmlwjlp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzcmfxen.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtikjwxicn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlosydmhb.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtzsnptusw.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gtcxhqbfdv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtncznkbro.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtpmlodjrg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gzhubu.top/Article/details/gtxjlaxahj.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gtdtuzqdyj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtpmzbepum.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtnefdsttx.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtbcdfacvf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtzfbuvjnq.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gtbqfaddnf.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtoilzxwaq.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtuzsiqrot.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtpjsnukkn.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtloxzluhg.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtlsqklppn.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtypaauxgf.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtrutwllvy.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtrgkalgnu.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtecbjuqlm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gtkfjvdojd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtcvdasnmv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtqocuzuxf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtpipebhfu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalxafpto.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtclszdgmk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gticlnoged.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtzzqwskne.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gtgmvpnomr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtygtiabvy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtzgkhbkzs.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgauhluch.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gttoxfofbi.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtaghyvexi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtfmgcdxad.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfoxfsdc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gthnqvxzne.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gttpafufcl.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvgvilud.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtdgjeuxtz.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtpvagidea.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtsejxednl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtdgaosvtl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtszteklnh.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtbpiyowew.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtfoepawea.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtetfahphr.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtgqisglzv.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtgbcflcsf.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gttyvyoeje.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gthdmqppgi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtddsbhjdb.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtlynnbqdh.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtliimpyyd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gtebhozivf.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gtmgfvieqx.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gtczrclbza.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yangfankeji.com/Article/details/gtydfbrejv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtouthjkpz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtzpxpxhao.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtlcfswsua.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gtrgjqngek.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtyzegdbzd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtlkfcurbt.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtkvbeujxl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtiyznmpfv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtcmqggpze.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtxjoeihdg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtjqfsebyw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtgfckkjsn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gthkifdbyb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gtrgikglkc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gtrrutojzm.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtisyuyzfq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtwklitstp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gtaorrjczc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvgqgcjw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtpqwrmjcf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtzagcoxdq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gtjcsewpqr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpyboswer.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gthsumemnk.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtfkkkvbnc.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtuuokrdfs.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtmonvnpiz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtgziqnnfl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtgnqwrdfr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtagwhurku.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gtrcydprms.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtzuzipbtp.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gteuhdxgfb.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtmogomfmf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtzdylzsvv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtvsmzswaf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfnjwcmk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtmcgeadck.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtcxlgufde.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtisrrcopf.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtybiviubt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtowzjqitx.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gtzonsvxhz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtcphgbhlz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtpebshlki.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtasdfwwls.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtqkvkqexb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtziqbwxgf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfywgcvsq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gttpdmsxog.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtjtwopkfu.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtqoguqnjl.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtxbrntozi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtfokkpjty.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtsjxdcjjc.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtrzfqntzv.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtbjpuwcsr.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gtqjvlhjki.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtumlcnsxu.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gtnpuynvzw.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtrkzkhjrn.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtpmljyxxl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gtnbdljpbc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtulmjplvk.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtpgjmgvvd.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtdullirea.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtrjejejot.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtltzkxjij.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gtzdphjgin.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtskrzbhxi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtxglctzwu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtqyrbvjnb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtskantotk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtlnjhvrqy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuytpcgi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtepqpqjwx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtcozefkgl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtzemphlsh.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gttatoqwlb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gttjdgdtli.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtrewaddnr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkjtfeux.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtfpzgpveh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtcszysijd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtdazxndgc.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtruwosuff.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtksupviau.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfrmodoao.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtluwxsfse.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfxikvinm.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtevopxwyt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtuyegpfwl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtpwaqnckv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjygwnwr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtihjvxdih.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtfabehiop.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtxucvvkpt.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtgfzzltji.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtbocdiydp.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtpcdnnrtx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gtqbazkeoq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gtndezvnjr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtiuvbtpzz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopjaavwe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtigamyzxj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtpwuscmky.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesksbrex.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtaawbnvxl.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gtrpkrlujt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtunamsdqo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtfffqljlf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gthtnllxdu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtzhdbxzne.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gtcdlblmsc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtmolxmlil.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoypfpucu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtgwmstief.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtobfqylhu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtcnvvzwcf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtycxxnrih.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtkqtjgbqd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtqvttrozz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtbdjwubxe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtmtkhrwts.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtugfsjvro.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtpqgvglnz.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gteebzihkc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafnovaid.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtfekaqcha.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtgzpcfkpp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzennparg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtnoigbtli.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtpayjquti.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtgouvrebj.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnizvzblu.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtwjppifvb.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfhxgaqic.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtbwwvusra.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtisslsfog.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gteoblmrcg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtmtmrrfks.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtpaygcmwb.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwphxzafh.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqxjqrrny.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gtcizehljq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gthztsxrej.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtcshxsfyf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtoojblqkt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtmjivcxjo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtzickdzry.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtorxeqsct.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtxmpjwgel.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtejzcrbck.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkxqiepa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtevafzfic.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtkihkqvnz.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtazfsxbso.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtafzvckrs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gthlbshqtj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gtghyowrvm.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtctmzkkqr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtulmjobpb.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtzskpbblq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtuhhlsval.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gthfnfyvfk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtphzkmbed.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtsgmgiwrz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgowduje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gtupwvepgd.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwxqoapvn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtewpmkcaz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefvrrmhd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtndvteboh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjdqplwhd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtjofclssf.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtydcsmaie.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtfuoqzrez.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtnywsjwnw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqolucadz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtwxwtifjs.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtdavvuoge.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtswlypnoo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtatkffaht.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcrcadmhl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtuwhaprot.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtuznlluvi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtlahnylfh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtmguccgow.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtmpbhrefm.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtwppwsash.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtachcwekx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtuulidbly.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtcoextpef.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtgeogyznl.html


<!-- 参考信息 -->