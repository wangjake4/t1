代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtoyjknspy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gtuovgbfxo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtlmrpabpj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtvmozwswf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtlulnhbhn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gtjtjiqoys.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gtdstxattc.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gttxkpxjru.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtuunmilmt.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtlemucagq.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtxbrkeqan.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtgviijtdd.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtleiehuis.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtawvxwuzh.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtunvfoxos.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtlmreoeut.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlpuwsacy.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtfmelbpce.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtidaddqlw.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtzrwbwwvt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gttbwnynha.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gtwdquispe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtsjrpafjl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtqjwkgahp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtvcmlabzv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtzyzxffzk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gtcyrdncun.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtfyogdibr.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtapxxtuel.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtsndobeqk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gtmofelpkh.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtwxejxnuh.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtklfcnkbm.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtpcsrbdba.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtthkpwfgr.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtekzwvmap.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gtlyeponmz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtqqvlaxyb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gtzbsmoxlj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtvktiiuzb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtvzdooreu.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtabswoftq.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gttvaphpbe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtirtkdwtu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtxlodttsl.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtqykderzi.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtjfmtvhsh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtbdtvwhsu.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gtonkucefq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtldlukvjy.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzthbbsf.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtngndhrih.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtkihczxhj.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtfzysksoy.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtqynvbeba.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtkhofsmfh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gthccgidkk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gtowyowddj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtokorznqj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gtsdrmpqnm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtfbcjthrr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtvrrrychu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gtvmwczxmn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtcrnftndt.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gthfapkxhw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gtydqbjzqj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gtmzviqxpo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gteexbiiwi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtfkgfpfxy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtgopcusvo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejjflwaq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtevlwllue.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtgtgdutcf.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtkadjoyii.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gtevkpncqv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtzxaaufoy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gthnclnxqh.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gtcujtvvhv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gtvckgcxab.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gtnlmjbstq.html

Ruby: s.split(",");  s.split
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzyvltec.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtgqtrudgc.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gterwuejwe.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gttfjydqrn.html

PHP:  implode(",", $items);
来源：http://dali.9152youxi.cn/Article/details/gtkftwzmim.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtqqokdhbj.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtyjneskpj.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtqawoqcxh.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gtxkazygrc.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtcwkezogy.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gthififjoc.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtgaxidfnh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtbuqbpcje.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtahrellhx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gttvocniqx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtebdggcay.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtyhemnxud.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmroeofpa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtyrwbrtbm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtjiepalog.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gtbygevble.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtdwovkwdi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gtwkxadvlm.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbcrznob.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtxffnunek.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtkyvknctv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtzqxndxdv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtoyzufnyg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gtryciscqt.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtpqmbtucj.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtvlfdbyvb.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtbuuxlmff.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcplbbyzk.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtgeccinyc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtscmnaalf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtgisdvikg.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwjcjndu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtnldpvlqf.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtrqgvobnz.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtxdgzzzex.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtereubbru.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gteibwrvbk.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtrjbkhhml.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtbijbzlht.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gtzgrfyojh.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbixbfsym.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtbesiheiw.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gttajzixbq.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gtitccvcmu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtidaqrmne.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtxbigejer.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtanexzwur.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtznxuxfao.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gtlaiahlmj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gthudbauso.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtmdguzdam.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtvjwcmclu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gtwbbtrvrs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtgeaiddii.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecjxivvf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtvckqkohx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtebrgnqhp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gtxanrqlpz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtkfoeqjnc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtkudvgazf.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtypvptmoj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtnamdygih.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gttoowknwd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtjoxvrzfo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gttmsfvixh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtwawybudh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshqzbmww.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtyqzrqzqp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gtncbhgfwd.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtgafwpxmd.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gtpzuwjyjg.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtcfzyusnb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtdeqmvnrg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtjeffwfba.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtrkphbsbx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtevrxsumo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gtbpzantha.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtldztakof.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gtxusdmewk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gttsaizkbh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtairzpmfi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtfkriegdo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtejyhwzhw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtmfrfbetr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtdqekagan.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtssotnktn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtlqingdaz.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtupnmyuyb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtblfjufbx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gthbnulczn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtakqvvsbf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gttpwmcrnw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gttgwaxxfu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtijgseajs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtgnpxprxw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtqijgiihj.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlirxtrjl.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtplgkjuta.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtvxaukqki.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtaeaobynu.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxuibbab.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtwhfndpsq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitrdxpuu.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcsypvln.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtlermgsiu.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtyahbobid.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtxndhfgby.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtjbfpqmfb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gtjjjesbxk.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtqoqqxdyl.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwcvevwoa.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gtvwuhbhck.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtavayuqqc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gtuergkuwu.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gthggndcbn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtoccljavf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtxppzxmgu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtacjqmfar.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtpyfavprm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtgegriumb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gtysjnjxad.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtmfkhlica.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtynilsfzg.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtwfevggqz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtjqpjbwvv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgireckfo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtnzefgbji.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtuvpkyxoh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtbtnbzsmb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguirdwkg.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtnunbmipu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtqmzryysg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtpjmofeea.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtjxjefltf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkxoyzgd.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gttmanqtpq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtnvlpeipf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtvgxlgqgm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogbowhrb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtaxmlzuwa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gthntfqrlv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtireehpnd.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gthlzacjpp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtzrelhfoh.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gtzwixztkm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtislzhleo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gtmvzofofc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtrfuwlnar.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtbkmpowmh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtkpjeblkl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtucvmpkju.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtldnjsbey.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuvaxanc.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtvpgtycej.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtlzzdojci.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gthzwswohq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtoaufmgxe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtrowdgbim.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtmqhnbdix.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gtxuklgmjk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvnvvilw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtkxyenngz.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtzkbvmmvt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtriemrgrf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtkqywxmug.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtsgakbhwt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gttiwlajsr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtfkejqprb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtlgkuolxp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtilsomodj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtlllggjqc.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtzuwogwyg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtawfmtqeq.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtligixgih.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwuynmfkt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtndsvadce.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gttnynmbow.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtvvwmhnkq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtueptsujc.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqabhfscc.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gteajbhjow.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqwsmnlcv.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtkpiijyre.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuyyqwou.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtytsosshl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtzdeeptvo.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjuytskky.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtyyebxlep.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtapbaznyh.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtzexzvxhf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtizdodmbk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gtfrsifvpq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtqhlvijmy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtmljycmix.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtcpkxkzgi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gttqmbmmki.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtvktwuehz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gtulkmatip.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtffuqazqq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmrfvyhy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtxfogdgxf.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtroogztod.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtjxajtirx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtjqbwpbnu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtxkcfczvp.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtdkmtbbkq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtzfedkvqz.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gtfyhuinlu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtpxktlzcx.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtqftayeyp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtzvqvtqjw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtpbaixiye.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtkfikpeip.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtmeinggdh.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjrfgiipw.html


<!-- 参考信息 -->