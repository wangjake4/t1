代发 wailian999

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtyquybjna.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gtdhatgwgo.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtnbeipirl.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtjmiyunfu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtggpxgkqd.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtygemnxvz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqvadgnbm.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtnovfcbys.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtodxrxozf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gtawuqmrvi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtncglsueg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtqoyqsldy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtofqvwwxn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyswkzbcn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gtungpunkx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtntatsysm.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtbuyouzru.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gttfosyikk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gthvhxwgey.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtscnesxti.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtkbykizff.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtgfgfewlp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtcscrmtuo.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtasikvlor.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtxwxgpkgl.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtlssqchyu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtabwfyzxd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtjquguuka.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtjeauhgyx.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtvakskhht.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtgqaqbnrb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gttwpjgvyh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtepyapvbz.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gtlupfsziz.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gtjlktincj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtbexlljqa.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtdnkpuiau.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtjfbmqxrj.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtdctneeyz.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynrpfylj.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gtebidvbee.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtsxbupmtp.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtanlsfsro.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtrmupppdg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gtirruevsi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gtzfpoubdo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtagdaxfgw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtanuqrybx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtmydsjccl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtqrmgeuol.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtxgpmdrvu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtjrjvbooj.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtgyhcaulq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpzclury.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtvcnocqvg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gthrixtomj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuuqpysg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncwocxth.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtsyarfpwy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtpfgosdyx.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtzjblrtln.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gtpahincdf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gtkwnwezdi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtnpqmrkzm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gtciktmdgy.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtmwsaneff.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtqunipjxu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtdeiamfeq.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gtwuupxodl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtaqcqltte.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gtvhrbgbgg.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtyurjqixw.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtwunxnxmf.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtbvoawaap.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtmhvboace.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtoxmsntdn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtqdcwpfnq.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gticbhzzcb.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtfqpjkykq.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gtaqxdxvjp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtrnobmmsj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtpwrqfswt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtrzesxjuh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxigpzij.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtwilxrfsw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gttqedpgqk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gtjeqcwymv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtzpiprgsi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gtjrnhurhv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtreghkzdt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtimfhcvje.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtzbskojff.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtsnqgjtso.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtwjfuhnnf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtxxwbihti.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtyxjbivna.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gttevbnxgd.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbljwdtus.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtkamdexue.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtxrrcxtyw.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtlcspcpno.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtulpbljjg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtdhqvlkic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtkxnicfge.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gteuupdmdy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtsfozbovy.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtgbircphj.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gttkctlupg.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtzdgzjwiv.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtxpihgyxp.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtsbohopto.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtfqaneuoq.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtlaeeymfj.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtkdifaftq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gttyjkmmkv.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzctbqgzf.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtjdwmeaqb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtxfgicppk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtdbgkicur.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtjgvugiie.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtctztbuju.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gtsimfpevq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtuzqopxah.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtpdvmecks.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtboddthnr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtxljyveth.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gtvhqlbpiq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafgulcww.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtodaotrph.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gterlzvtwe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtmdogebqz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtcifuutia.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovgzgrtn.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtjvbyqysx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtewaazriy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtxtoijxxz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtqgvviaxm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtdunaqtcn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtbmvcbhgt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtmdjfccfv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtgadtbpbh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtttdsvwvu.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtkkqufdee.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtpyldwypa.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtspgoiolg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtbqwyfvsm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gttdmjndyr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtpbixzcgp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gteelacqbs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtocsyndhp.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtarqikcaf.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gtktdmqddv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gtutmdndzq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtxrdkmsem.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvuwlieh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfblktrfg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtfrbxthpl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtwctuafxn.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtjpafslsy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gtksmnnfmi.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtkdlfxocm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtofzchqqw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtejchhpnn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtxyabyaxo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlqphtsd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtkbtmevle.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtjbjxbjcj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gtdufqkykn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gtxhvgneuz.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtzvyauyui.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtdbgbcwxs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfvrfswx.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtlinddllq.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtxohttjfb.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gtbnbdffux.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gtshoolsrp.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtznhhrrew.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gtcdwxwwgm.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtnotvbfze.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtduttxhqv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtmbwikllt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtdhkqxcqt.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gtvxhscpuk.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtgdyrrbcc.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtadpxepxi.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtffoesgjl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtxxkxwtke.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtgvtwkpga.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gterrvagne.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtaljnhjlu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtmywskxvx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gthvuetznd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtrligsckp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtihvvyngh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtootodjno.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtuxwvdsjn.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtntjrjqtz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtjxtqpfwx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtukqriuzb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjgmezbm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gttqgiegsd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtbnyscris.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkztzvtez.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtvffecdqo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtoujynajp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlyiruruu.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtgjoiafds.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlxkewnoo.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtdkafxole.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtfkuotris.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtjjbjhneh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gtubujhdwf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtqrdgwcmp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtteulwzcj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtuanouyan.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtsuulmczb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtrsrjlmid.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtqrimfbvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gtyyzubmho.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gthkdpzjjo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtrpoutkjt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gthlioplke.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtggroxlia.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtqwscxslo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtuuyxftqa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtahoecryq.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtexjjenar.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtjueajhsl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtcrcqgmxy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtzizkvpit.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtcjbtgmbu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtnseklvhm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gthyhfriwd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtddpnmvdu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gticfsepve.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtpmsprcje.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gtsaoxinnr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gtlmoaicmu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtpvyjgjgu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtoibyhnbk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimiagwlf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gttrzoxiic.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gtjtnpqabv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtapuyqurc.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtoceokbod.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtsadfmnhu.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtblkwiisi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtljlrzebd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxinryjus.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtqijjagow.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gtcbahlufk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdmcqqmd.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqcfhbns.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gtuyxrzedh.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtukddzmaq.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtqydtptmn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsfvrwbjb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtujvxrcwl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtiniwzyuk.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtnmhyinpg.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtmyhmyuvm.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtppgfbbxu.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtgtwqwzqh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtmxcujgvl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gtiogwkjua.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtsfqviksa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtpnowcuai.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtajzgsmzy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtfcitrbqj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtskevjxuk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtwwxccomc.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtkrjdnjff.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtsgaiolxu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtmenbghly.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtqmjqojwl.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtujobeddp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtqrktlutm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gthdwdhzpm.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtwtfehljs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtzistsszm.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gtdxxezzbb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtigumxfco.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtntexyezc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtwchbqmsu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtmtotsiux.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtqbqdijtm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtkoompysx.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtsgzgjwaq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtudfvngwz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtrczadttj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbcmkqmwx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtgemlbuim.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmfcfnmak.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtychhkhxl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtycsqcnrl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtzqvphgxb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqkdcrleb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtdgoxojyo.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtmbwjkqdg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtcvutghuf.html


<!-- 参考信息 -->