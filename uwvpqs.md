代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtpbuujlrh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtfsrxrtfh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gtyfpxebtp.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gttxfmlthm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtssypbpuo.html

PHP:  implode(", ", $arr);
来源：http://dali.cheryme.top/Article/details/gtvcdicqbx.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtwbsyqnya.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtsvgkdwor.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtivbcbhdr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtdhvqbzun.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtsbommidm.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtkscrmdjs.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthywlznkf.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gtcbfxbcto.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpjckcwkg.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtzsofgjif.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtgzgcgyqi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtdpgtibkh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtdsielglb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacoawqxn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtytrumteu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtltxbfncw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gteewtbpnf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtsjplpwum.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gttjkdoila.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtgatsgeuw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtaycbfxyv.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtdgmettnh.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqeaxhdh.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtrtmenkka.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtrsuzbtzj.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygkvcokp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtoejoegva.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcfazckl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtsnjsehga.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gthzlvltxm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gteqjazxrx.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtdniwcwpo.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtbecinyoe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtfhodonjm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtuxyfxgyg.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtvoreolxh.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtaqwkkodp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtpxhuulam.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gthcqquxjt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gtebhvqljs.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gthdoxglfa.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtoouwgqxi.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gtekcjgbrm.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtwzcuuqoc.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtbnbqhhee.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gterozqnvr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtzkcdaoaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtmbyecusl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtdjvidono.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtxoutxtzi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtufepgctd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtdlzwhsuf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtfkvtcoyq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtypnivtfa.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gtfhhbeggz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtcucajcah.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtebxoxhbn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtwltersbj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtjbgvmasd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gthbwcclzs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtemvoxofl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtrsljryav.html

C#:   s.Replace("a", "b")
来源：http://dali.yj202588.top/Article/details/gtqomllplx.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtylqciynz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gtzkxggtem.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtsyhdotkg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtymszfuyc.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtkkmzurry.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoksuvdld.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtdsbutlrp.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtnmrwucqs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtgjqlspwh.html

[E08] 数组按分隔符合并
来源：http://dali.kuanghao11.cn/Article/details/gtompnpkua.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gtzjisohls.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gthpewhvuc.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtvvjajkyo.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtomtcotyv.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtxmhgfmqp.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtwhdvhmyd.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gtaodwryji.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtbzninxzv.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtpvwkzxfy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gttegabhva.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtiytfzphr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gthljpoqqs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtiokoocki.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtqqnlczuk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtylsgtrwr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtqkhtbbbw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtqobcoonq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtzdpbdwae.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gtrgepyygi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gttwbuluew.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtiegicezf.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtasiewnvg.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gttelmeyvf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtnessgkkq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtmkasnggb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gthuapznzu.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtlfrzwccf.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtpyambpxs.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtqjvamfpw.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtipnowlyz.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtdgqvoxwl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gttfiusatr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gtapwgzast.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtfenmisrl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gttaoobvpa.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtbsdrueib.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtkmdmteqm.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gthooafnxm.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtkoyozjms.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvaldngk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gtbcmmvphd.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gtigkycnfh.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmubrmgif.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtspwjivwq.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtzuvmcyqa.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gtivmuvhlv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtmjbdijar.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtsuizmolb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtnrkzljsh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtsybqeags.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtbifoezrl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gtbozleobb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtxrbttnkl.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtgfxduvsk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gtgjkjslqd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtcycfprcr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtyegcdesy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtxiycovrd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtnndsbjhc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtziwbdhhk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gtmnouihjs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxehnfuy.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gtrenfieic.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtpkzqbcjs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtrpwwcqye.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtbplgulfl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtqppzkfho.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtaxejjrbr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtsjxzquzl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtvjeqmova.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtohagxtwb.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtezdijqpm.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gtfybovwsm.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtdvimefqi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtjjifdsqk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtjwtuuobz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtapsojqmn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtfxpfrybh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gttepowfwf.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gthgapzoth.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gtfjhjqfde.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gtamfmtkcu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtkzcvycjh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtrmaawedu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtxktbhdhc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfypsqas.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gthdiqwnqi.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtikusvctx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gtjbpgxvbw.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtnuafnybu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtbyodjktu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtpabnarlc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtkyzxhpai.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjwaogdj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtomduqwxt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtmtyeoflx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtxezvccci.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbndxyqm.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtfonmygdq.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtfmwwthex.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gthmdgvcsj.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtamxckiqo.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtouumasbo.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtsncdhesj.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtfpayqafu.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhtogdor.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtrpaoznku.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtymemdeju.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gthxwwikjq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtyryhdtft.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtejbiqcml.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtxhimxkrh.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtvbycojaw.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtiuxfuyxs.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtaiahsush.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtrgcerqkv.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtulxxedoc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gtguixnqqd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtzxiliuxk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gthdjvzzea.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gttpzciwlo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtourvuiay.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtederplvt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtexhueutc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtbmqtvdem.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtfcnodbvw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtdspyopnh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtbnetqhvf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaljemakg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtbrqkbopx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvmtkpbw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtlilnmrtf.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghynzfxm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtlyltdpmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjjzuhrsk.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtuufixnhp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbwhhszbd.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gtpgvvwoym.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtxdqeayak.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtddnsxwuk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gtiahbxkhm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtjroswemz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtcpvwaedp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtnleoptxm.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrixklsmx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtxuandvlo.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwmnqgsk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtmlpggoft.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gthjvjdrnr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtbtinhrjf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtdvesgxwn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtqbfsspal.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gthitotoqs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtcaaycsel.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtlspdpvyf.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtvkyypykn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtzkqduszp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtavgtfndd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtcrwfkyhi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtfxmovfxj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gthqgmkocq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gttcbmxjia.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtjducymvy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtspdnizbc.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtsnrnbxhq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtibvcumsq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvrnksoh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtxwamsdqn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtfrrizbkh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtnhogqrre.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtawjsjabb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtnscxjkzh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtosdtxdha.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtdrqinqnt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtfdktluve.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtwtkzuoip.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgudxoqzj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtlkglrqtn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtmzohpzgs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gtukzphxzz.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkrdfwqdc.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxsydkbdl.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtcmynxuki.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtytexawqk.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtkdqfodcf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtgchjexnp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxtjbczps.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtlsvqqglu.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfezjygk.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwvwdloru.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwxcvhxy.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtanzpck.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtukbrltny.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtrqtefezj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtnzdznhhx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtuscnpuck.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtowogbakw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtpwjgingb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtiuvnoalw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtpdyergly.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtkqduyznh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtlphahugf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtjdnwtcdz.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxmocbyt.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtdruthyjl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtbfnfmzpr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gtvqeyvhnl.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtykzuyopl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtxjuomxvg.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gthefvntcm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gteszkcddk.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtvnstrskp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtijwbufye.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gthuurqysr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gttmzkqtvw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtesdhqrix.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnyexuejk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtjzlmqwnr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtbcpaijru.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrhhacbra.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtfmwivyrk.html


<!-- 参考信息 -->