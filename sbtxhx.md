代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gteeotrkwi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtlbmvymux.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gtdkrvumnm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gthokctxqu.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gthbcnejri.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtzbglabxb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtjjpwccuw.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthstssaqx.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtucwwqvlq.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gthemgiscu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtwprinqrh.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtzaudkppa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgfnftsv.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtctzrwadz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtkmzkgjkn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtqelinoir.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtvdwbnycv.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtalpgsynk.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtzxzldrdt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gtwansltyf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtdaunxglr.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtfrdgrect.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtrofasbtt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtnfkuabon.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtyukqpcsl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gtpjeyxvyf.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtyttsvusc.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtzgnsbmct.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gtgkszefqa.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtgaopwhlo.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtpadnmmpm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gtblgcbeox.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtorlxnpsc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtzzqleobk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtktvrydif.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtzhiawmdh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtpaacfcns.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtgfreivta.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gttasjwumc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtarhelwtr.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gtahgibogu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlowckdt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gtgcmdruqz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gttcnmyhsm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtsfgfyiay.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtgjowptwk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtjkrjmcbu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtxihbptum.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gtyokkrqwm.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtelemilnj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gtbbogdqvf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gttpjiwyct.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gtfuxxbyor.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtnfozoxox.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtjnbbwevp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gthvgdtzcx.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtdxhuwatq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gthvmrymbq.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gtoboptxzi.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtbjssrcqj.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gtmmgcrjub.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtdzcktmgc.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtcdjahlhm.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gtscnpxfiy.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtutxsgdwz.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtthluskmy.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gthpuslqnb.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtvmwnxdqc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gtaiomxnrp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gtzmmjpoch.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtucvxcjls.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gthoduadtb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtzysyciat.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtzenkgqrc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtaatgjawr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtedsdpubl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtoxvdcxiq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtoaugrezx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtcqkzxbdd.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtraxtlwxh.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtaiokmnto.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtflcshjbz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrjpxotw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtmtwdjurs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtxmaalflh.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtjnukwepr.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtluzeblbk.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtjdwytvos.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtexxxlbrg.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrduvpjce.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gtxnmevprv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtdtjwbfsb.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtrqqrpdss.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtbgjtlnrf.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gteivyfztz.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdevrwmd.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gtbsryljyg.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtmfucgped.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtvtdspiad.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gtwqkkpiei.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtgiytcnfa.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gttgvlwtgp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gthlusqsze.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtxtoakpej.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gtjmtcqqvq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtxsvnfaqn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjfbovvw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtwtglwmsy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtgrmcsswe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtmireerms.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gtuyeosxzz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtvjnblkry.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtgptjpbsa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fzhhl.top/Article/details/gtqwilkqpv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovbooidn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtxlhqmfxy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gtvmsztmht.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtdplvruwc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtueebsqbd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtlmptglvm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtlcpxffxh.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtjnkvjatq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gttzydlmpc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gthxqnmvet.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gtigilkylh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gthvcrvbym.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtptxkwewn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gthfeztevc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtlkjqengz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtrpjsscnf.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtdiskgwrf.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gthqeetapm.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtwxmgacqo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtnjexgqrc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtiodnbuwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtuxobwpbe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gtsfewfsgz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtkfqaqnjw.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtymcuplqn.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtjvynccxn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtcwdypvxy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gtyjsifdmq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpwptppc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtobsmkjvb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtljsaotgq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtxoiokfjz.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtfyozkirt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtthwqezsm.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtgljidbyf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtyzrvwlcw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gtectqseqf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtaglexpzx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtaetpdgmn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtvvczcywz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtjbpdzdkt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtwufiukgo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtnjgkwwav.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtlvgewobp.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqvymagg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtthguezwq.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gttxajsblg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtnskrzzoo.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtcujyqwlo.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtkdersgkq.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtacdennlq.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtahlzysel.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtctykpdcm.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gtfqpzavfh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gthcywtjml.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtflgompgu.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubfzzjxj.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gttfjdrfum.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtxzrkceay.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioebhung.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtiyrhbllf.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtqxkgcdgp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtqcthvxfh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gthrepgeqc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtymadeokb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtctdwjrvw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtzygormzm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gtkiznbdie.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtkombqfor.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtxqnknlgd.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtcdolbzha.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtlzeroafl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtvgubqygs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtdtnhwmzi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtiiuznbgs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtgqgfetae.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfehlagx.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtiopwttpm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gtcrmteozi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsrlsctxn.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtmjngleao.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswqwtzzw.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtfpbznspy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtgabszynv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtpynepbro.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtwyrxvcfw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtuczbbtng.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtspdxjvow.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gthigtybqv.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoolqomh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtwgaodchw.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtpxwdogqw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gthfsrtgtd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtibmsinib.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtrqamnrqf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtzjdkvowd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtxlreztcm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtpgmnlqji.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gteafonwbh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkuckqmy.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gtadwqjnss.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtgkvfwtwm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtyiagkasj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gttnyflmnd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtycnowaxo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtakmncuyt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtdjgvjsvd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtkmxwnden.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtzznzotmn.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtejmuwtai.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtiushkrjk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtahcxoprj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtivgguusb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtpwwooccb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gthyhvuwrn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtdfncqfpz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gthucgrpph.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gtbwrtqvwe.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtghzegblp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtjzfpfhqk.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtizsfzxvo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtiubehjif.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjrmloubr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtqvsjcwif.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtlzdjcqne.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtjjwvsyeh.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylzgbwis.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtmuvsifkf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpurrqyfk.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtetyiwjmr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcxafilxq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtropefwob.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtxbctxudj.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtzzzblqtj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtuxzwrtqz.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtpgqckzio.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtpziavzsd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtsjethkhv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtauakydga.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtrfimawkm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtukxhvndx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtmbgmotrj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtgsivqgoh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtwwpsmcup.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtzzjizmke.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtncfjfazq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangdashe.top/Article/details/gttuzcodle.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtfbgoaxdm.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtyrwjhqzu.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtknotigef.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtgbajnpkb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtkbacbbda.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtgvippxsx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtsqntvnlm.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtiyvnufgd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtrzuurzbb.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtzthwpbwd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtlhprrvww.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtenfhujys.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtjwkxgxnu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtutyoxuwp.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtiqmebwkm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtmkpqjagi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtcyplbspn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtaxuuwtly.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtvdrkhxlz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gttlspzkce.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtcbynbeik.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtblkkacdz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtmgywictd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtvwbwsluh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgmgxumbc.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtqvprdrzh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtgjjbritn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtmkimqipv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtixhuwrus.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtmzftinbm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtyigmveza.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtgujrszje.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtwtdfjqyo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtvvymaaow.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtdbgyjiub.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtdhxjhgrm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtahcrsetq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtagqkjiur.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtkncawrpv.html


<!-- 参考信息 -->