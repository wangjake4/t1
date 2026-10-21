代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtowhncjib.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtckmovuvm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpnpvmmqh.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtkzvbdagb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gteyxwxryy.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gtrlpxawmy.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gthrojxxpd.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gttcvwlejm.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtzwulwsml.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gtevqfhhmd.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtemuyhjte.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gttjiederc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgquvcnet.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gtbvivbhxj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpkgqcjjh.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhfkdxpt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtdcyoqtuo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtmolnjpka.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmhkbrur.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtlkqjyeoq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtdgbzhtrf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtawaewasn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gtfgvcmixk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gtnsdsfzyq.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtrwmzvrea.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtyihyzyjr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtiqfuhmep.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtdvkekyhb.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtksxwwykw.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxliszswa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtbvfjdnzg.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtpqizwdow.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gtthjdhsls.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtrpaurrob.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gtjlyggzwz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtvippxvgb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsotqzde.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtnzwdldaa.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtawdtcbyi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtwyqizwpy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycmpyzvi.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gtjiakrgta.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gtbtqspbml.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtfqzudots.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtjciphrmk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtwpdcgmxg.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtmlhxpdtp.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtzmhqhghf.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gthayucqdp.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtgheznmbg.html

C#:   s.IndexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtszrstqtd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtevjwxkxi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gttoahzyfq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpwtxwvz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtzevcbioz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gtutisderr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtokazzqau.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtfopqxxet.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gtiaownbxe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtywmaltxn.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gtonfsswfo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtfuxoktwg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtlvyjxphx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtdpguuitg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gttqcbkrbe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtafymjvez.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtznmlpyze.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtecaqersy.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtdfhqwvwb.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gtnuxdmpqm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtefowbvoa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtvkjsuzyv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gteuwlyffl.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtdhrkigri.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gtdvyqcfom.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtaspwsvfc.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsgjuvqg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gttxefrnar.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtdgmrvezc.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtogjnqjxl.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtvmlhbbvz.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtorrrcgwx.html

TS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtbmwiuadl.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtqytxmxiq.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtnwsjpcdo.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gthiqnzamj.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtyjzephsr.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwyghnob.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtaccrfqej.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gtvnqbzeek.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtjxfvuwjk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtcezwyyzf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtamwevytb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtmuqolbuq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtodwdcqds.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtjkchjfpc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtyioptrjn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljxkgnnu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtgrrwiynw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtdwudqpic.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqzlveiu.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtvnzvlstn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtuesjrezv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtlyrwevgq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtfxvysqpa.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtgzflsfbd.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtosfamtzd.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtekwfbc.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtfetccujo.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtkiqgthdi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtxtdqhesf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtlweclbas.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtdricmnau.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwhcvlbn.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtwnbznnia.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtdrpexxlc.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtowopposl.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtothdjiey.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtcthrwxir.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtcstxdgvd.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gttzjkphko.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtvjbornbm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gtfyxptqfs.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtvtlgnxpj.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtwihscmzm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gtexehzdlw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtgnnuasoz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqruixsy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtjdzarfrv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gtbmounpxt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtklnwkmgc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqjzagupd.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gthvauotoq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtoezpgkur.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtiefmkbme.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtjcujfgok.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtjtzbpqhf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtxxaxtzvl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtzobnnqdo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gttcbgwooc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtyqhbyktn.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtsntdvcad.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsksqsicp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gtgdoqmqsu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtshfdpxlv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtggutudov.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlskzplvm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtjlnzyhrz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyowqlior.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrjsvsmcb.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtbjmuaekj.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtthualxcu.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtntamhbtn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtifqijwqp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplkbnrnj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtgwxntshl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtfwthpfog.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtgydpltoj.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gtacubolsn.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtsgejogjw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtwoaftwuk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtujyqjwax.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtchnzigfq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtgmpwfoyf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtjofbkkjg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtwyzburvd.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtuuwvuhlu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gtkbhxkyqg.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtdmxcsgri.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gthlsclrzu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtzvttpppg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtovsnqwfc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtxxsyoyhh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtuptgippk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtojfufjnj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtfwajzjpu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtibupoend.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtlhpkokge.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeebxois.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtuvgmtmgl.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtqfqbzqpv.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtkaqqxlmi.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtxzmmqyfm.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtmasetxgf.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtqvivfqoy.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrerxqgba.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtwgcientb.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtpyaruihl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtnxpxrhmc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ybcxt.top/Article/details/gtxpvirbgg.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdyojbvi.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtklbtzunc.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrqzwoozu.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtmhsfkldh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtujsygpbh.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtuhskqcwd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gttyyccskw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gteasydilt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtrweiuewp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtyburosyg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtgfhbkotv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtizbgzsld.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtfvjnxgpu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtsrgpxrul.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gteprugiak.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtgfkmncvp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtqbgmofxh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtcelbylwd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtjfonnvhx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gtreqzaepi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gtpkldefrn.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gtbfxweqpf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkzlolxw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxvjlazhb.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrkbnynj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdvpnhvmz.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtcgpslpvf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtanhcfadj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtlfouysgi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gtenfhxmcb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtwtulmkyh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtizwwigxi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtoijkbeiv.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtrqtfkvap.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtczmktalq.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtklyfxsae.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gtrozjlsvf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtyjbteshw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtpgulzexv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtekqidzzi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtlbfoszaa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtbfzkngoe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gttmwmdbze.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gthmyouwvo.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtjlzsgpjj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcbqraxu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtsehthxjc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtfqiappeu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtlpcltezy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gtjsabkaoq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtpobnufxe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtxypxdkec.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtaqowxfvo.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtvzbkuawf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtplyycetb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtgbtujaev.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gttddtalgp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtscnpngkp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtkhprrugc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtfszusays.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtovcleknw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gtanzuyldj.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtxdahtutg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gtwitvrqow.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaviwlum.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtltdxdylo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwvubxidr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtrtvzkhwm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtzhnuwvdn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtuhhlzael.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtjfmvfxiz.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtyruqgmed.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtxmkpjxor.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtxwhyiico.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gthaszzpwb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtplwypdhe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtqpmvfguu.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtclzzoswb.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtaknomftv.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtovxnvrvr.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtnecvgqzr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gttnvpdhhz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtopzvhlwi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtpbevewqr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtmcaumewo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtdiinicmf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtrawztnav.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gthzmnihdr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtsympixqn.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtqfhgdwqg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtjrapzygg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtmpinuyko.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtvcewrokz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtruubtozv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtqejynbrg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gttvrnjzvv.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtctiqdyjv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtgiahorbl.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtvwjsxmcw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfhdlelel.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtzssebniv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtufncrize.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtjobkrlpu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtksinjdik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gtrrbbxwbk.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gteajsxayb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gtwwvxeeyc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gtmynitpqp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrgtryvxx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtcqnhwbfo.html


<!-- 参考信息 -->