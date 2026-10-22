代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtjcehclsm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtospovngl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtuttuugmp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gthegpbfkc.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtgvytgick.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtlrgnncxi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtklpdaceb.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtndhzlgvb.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtvbbokyte.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqdgxdyl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtzfqhadju.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtprbffciv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtitvlmqic.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gthosgxitr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtknxbmcix.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtzojbagof.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtxrfetkzx.html

TS:   s.slice(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtkojqwsow.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtckyohceh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtzuqwrjhr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gtwffmgyzm.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtcxjzllrk.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gtouxzuvjm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtvuksmuub.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvnolqrc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gttohjzqvh.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtheydruzt.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtkpphdysy.html

Go:   strings.Index(s, "x")
来源：http://dali.aizwys.cn/Article/details/gtlfrszhqj.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtaqinjoxx.html

C#:   s.IndexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtchhzfhti.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtzwcpbfmt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtsyudqpfx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtgvwezaic.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtmkbbzbqt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtwfripozc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gthrwvhmog.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gtjpzzzaay.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gtfryapjeo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtwxqxspze.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtfwktxdtr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtgbsibziu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtlcuzxtqj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtemlijxfg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtdjeawwsq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtxbmxrhjm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtusipdgmf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtbgyvcdxt.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtbwqfecbp.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gtyriqgonx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtlhhlbuzt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtkgijsgje.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtunlajnhb.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtnzkslwwx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtvukhfkfb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpuvvckj.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gtgfmvbvwr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtbohsogwl.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtvolnhwjj.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtzrirhejk.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtqptaijyb.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtgrwiqmzk.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtsvuogjvk.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gttsgthnfb.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtpmbyvxfp.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtrejvojjb.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtvvdrdmok.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtvlwvaktm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtxbmsjikp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gtprvslder.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtgxvplcun.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtyuiexwql.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtxcgllxei.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtiodqsioa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtvfdcrfyf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtrfsuxiar.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtbpxibdkt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gthabszvcn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gtttqidvia.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gthuiswjuj.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtozzpfvyj.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtsrkjtizm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkwcngsu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gthddyoifl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gteqhclpio.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtosygchck.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtxbqsbarf.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtxdgsnurf.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtrritncpa.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gttomtjfjt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtnwyyeewz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtwewyurxk.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtwnyokslz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtzootwaqu.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gtmbjylggu.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtypsclsyn.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtzquhwewc.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtyatwtlvb.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtriaccnbj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gthqxemvpu.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtsnobivgy.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gteesamyqd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtnoxoyice.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtpbxeumkl.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gthyhvglpg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtrtkwmrfq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtrtcacdwo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtquzbothr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtjcrvbqef.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtartdeute.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gtzfzfxndp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtbqsaezcn.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhbfzpej.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtfjsxwcbu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gtcbctzxqc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtbcycblgo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtxrjjkoak.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gtuqnvkcnb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtkbucwahu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtvdgfrimb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtflfomarq.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtpystkhee.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gthzcmyycm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtstbzvnge.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzgtmhupj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtfuiduyli.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gttkkjhltt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gtljqlrruo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtnllkskye.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtpcixhefp.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gtxcgccqxg.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtqpzappbk.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtxuqvbrqd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvzhnflz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtjtydahhc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gthvkfhmxo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtusnhjica.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtxllkqqni.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gtmtbsuhow.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtixnwmrwn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtwufnhgoc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvqcncfks.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtswglxvth.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtqpcqwagc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtxhvnkpoa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtsmoyvcki.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtteipzvtv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtiacelkun.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpauulyf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtuqnxynbe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtufwftjkt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtbnvtpjai.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtcryqstxr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtcnhclkmr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gteaxzngtg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtuifoqlxi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gtmrreufnz.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gtdpdsfprw.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gtqsbxlntu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtnvwgggxu.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtoqdctiyf.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtxfhpfiti.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gthcqtzdjg.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtxalxnanj.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtblaymrrx.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtkmdgprak.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gtmavklfsc.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtaxybidrj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtytfdujuc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gteclofihn.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtvgwyrgmc.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtrhkpkgmo.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gthcvhwadj.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtqwifbhrn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtmijmjctc.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gthjmuuqrq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtebwyjxsa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtljeudsnv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gterigdtox.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtlfrapcbq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtarchixdr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtfojcdglo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtdclutjcw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtzedoblwe.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtcyreojib.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtudkafrvm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtebvwxewu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtkvypcjdd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtyfmrdhmd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtdfkcphvq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtpflpwged.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtvvmnenwb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtrytspnre.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvecjeqvn.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtbevgredb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtljsyvzsn.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gtyfjfqrpr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gtkwxkyhyd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtbcfdsynr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtunxfvuji.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtcmzkusvm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtjoamrjpo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtwkrmrcgd.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnxlpjyt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtreuepxmu.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gtocfhlhke.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtmpeavpkz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtqjsxfxtt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtbnrbgwbj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gthzxpnpzt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtjblsqwvg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtaujktzjm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtlgknssiw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gtdkvxkheu.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gthrwcbkjy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtlbkjwmby.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtwllttvps.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtimzhsoid.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtcrpmlqqq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtiiujbfoq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtwobtzeck.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtprzclskr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtjqmbhssm.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gtupsgluan.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtaptgvdcz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtjkzhbkfn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtftdtemld.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gteanrehsi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gtfaadoppv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtblivgvon.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtiaifekra.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gtgpjjvacb.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtwwjofcqv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtqqxfaymk.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtoaumlnoo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtkpwpmkzn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtelqwnjvd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtqstsmfny.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtvmlbkfqp.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtglptmcec.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtebfdstmw.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gtqqquckda.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjtnskgew.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtyvbqlkxl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjetkbsv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbxmlcuzm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gttqedsaag.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtfirouxtl.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtbmzslnzp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtybmheppc.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtbwcxyhfv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtspcbvfib.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtuprhhjah.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtzbbgbohj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtrxhbwnza.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtpvtjhihd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtgsskgrms.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqnynofu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtrijwotxc.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gttapjmxvn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtbcoejyro.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtnkassokm.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtevcifovy.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtejwuxwqd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtwxvmtjie.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gtongvurbo.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gttrxnqutq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtblkyjtmc.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gtyvywrnec.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgdrcpqnz.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtbxpbsina.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gteiqjffdj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtgkhecyei.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gttqboapvr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtgohufcrl.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqxbxhfwt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzbkddaj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtznnbkhtg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxbifqmzi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtmxducfcp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtzacmzglb.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthoqraslc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gtqcvooxot.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtrddapnoi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfibmxgs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbfmhdyxm.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gtxelrvalt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gttyvgzjgr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gtqjszsxcm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtutzybibd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuggbtans.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtioctxblz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtqnxcydyj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtgktvcqss.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gtfdjyozlb.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtpmdgnlwu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtpdwnyegd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtueakyyko.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gtrcyduhik.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtfihqvesq.html


<!-- 参考信息 -->