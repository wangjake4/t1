代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtqxfbclof.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtbzrunxwo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtluyksukm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtathzvttv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtoxwustlx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfikltsu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtvqitjqqh.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtrvvbnzqv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gtcsgfrdbp.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtjhlnciry.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gthyzugspi.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gttlhhlzrx.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtfomtlndz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gtnqbtiuay.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtdsqrrzkc.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtludxozdm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxwimfxcl.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtapebrmoo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdrrefeue.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtbilxjwsa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtelteubjc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gtvgxipufw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtoourwuiq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtabourvrb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtghetrisz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtpabudott.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gtrkivtgtq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtizzvfaor.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtkaebzuor.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtldneuhzf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtbnbddxet.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtreuhrlwd.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtwgmprneg.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtqkvgwjwf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtrxsmcgnr.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtmonwjnmv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gttqvlkcmc.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gttqsmphtr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtqgjksyqv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtekpllhft.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtiixrlgbm.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtzwqroaol.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtghkksiqg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtfehdtbus.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtewnemzhs.html

C#:   s.Substring(1, 3)
来源：http://dali.chenzaomai.com/Article/details/gtagrkyacd.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtkxsgpfxu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtwlrfbxvp.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtopqsqoux.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtfnoyctfb.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtgliyazfb.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtrrwrggef.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtpcqticwi.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtmoibnegz.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtdpvxkhes.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtspiqkhep.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvlnmelw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gtpexpiydj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtlnxsjueh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiemgigih.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtfucktziv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gttzpbutfb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gtbtdexefm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtqgdmskek.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvifcjhp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtajvnfskw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gtfndlufhv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyruqtgt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtxatbxrhq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtilbtdxjt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtemxsrzxy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtcpvlunhy.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gtjfeiyhxn.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gtafkhfgis.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtixjcrjzz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtvnczjuab.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoxagizc.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtipvcdxbt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtgmzmxgtk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkkqopwku.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gthvaiomzx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gttpmgbiyz.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtlclxxbvt.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gtgszsgzyn.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtywkdmhgi.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtvrnvqolp.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtavgxfren.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtgfxznghn.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtcmajibhy.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtlolzeigu.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtuzisbxcn.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtdeuqivfq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gtepineqcw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gtyvvbguse.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtngmjoutl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtsgzjcueh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtxhjiopiq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtnixuywxw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtvciffsju.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtqitpqoby.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebetzfmd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtcgfmuqjf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gttypfppdx.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtuqbehdhj.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtnenzkeop.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtzldcqudr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvfnkaqyo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gthfisotnu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoohyenj.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtyhtwcnrz.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtvcqcevuf.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtnzpjzxsp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtgoeyjoxg.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gttiscjedq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gtlmgcmfnl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtpqcyeyxj.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtsgtuolcx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtkktycroj.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtyxzlbheo.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtnqgfjxxi.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtbyyfyqcb.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtxfpqeuqq.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gthdqauxsm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtvtkcypnv.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoybhvclo.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtdhntfcbs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtuewdtnac.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtwvjucgah.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstquszvv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gttlvbjtqt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtjnxvwrvd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtftdhubmp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtixqdpkvd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtkeobarhc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtligoeqlm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtzzoocmvt.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtrvspqjol.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtydkalmzo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gttyalmaha.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtkccevhnc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtalmppnqd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtngyzpyac.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtimfnhfce.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvozuity.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtjgfgzuac.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtkjtvmaaw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gthviuarlt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtrdmfonqu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtzewyjxix.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gtrkyihdak.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gttutvmncf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtpgbjxypg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtxeyqagpy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtwqsqzddw.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gtrisxeiot.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gtzjnyjgti.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtuwgaarvx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtkfgltlmt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtgqtnrzmb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gtoohdxgoy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtbswaydxr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gttpdcdtuk.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtfeocbsss.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtsxdizasd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtifrqntzh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtwcfnlfbq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtecwlaxmi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gttwnokxdx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtwihtvciq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtlpfvqzlx.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtcsdjjlwm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtralgcbhc.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gtdatyhzzw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeqxggjh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gtdyfxurya.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtoahirspd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtnlewuggl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtzvebtoxg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtexbitahd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtvzdgcwym.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtjyjdzfpz.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtymipmoqv.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtdrgyvdff.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtnafjfimh.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtwiatyerj.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtmzbxojly.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtiwvxumhc.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtxzrsrbzt.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gtnpahzsns.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtfwxynyup.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtfdsqdill.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtemisasxe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtvcijmrtj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtfztnnpmw.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gtjzwmihjv.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtiigxhpjd.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtuymqyczc.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtvyukhhoq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtfhazjhuo.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtzuhhucqx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gtkifbmbpc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtxrjysbis.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtbvvtjrgs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtcilrsvhu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtnaiigvcz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvjpkyke.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtenetlpzy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtgcmpgmtd.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtddivnkfx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtylbmpdso.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtunbjbeia.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtpfoshkzf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtxgfslccc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtugcxinhb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtmuhbugvv.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtuldbmuyj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtiufcidrc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjclbhnhz.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gteoarevvp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqukvhlhp.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtcwaqoafe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtwegjxnbv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtekkpxedp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtmsbgjslf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtvvgqzlas.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtolacedqm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnfewlai.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gticcvjfcl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtnyyyiofd.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtwegnhlfv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gtzqamyzcv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtgxakqtip.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtcwuedkko.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtvfvxusof.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtrotbtaba.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtnicreigw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtmvujqqpt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtwhvdwrvz.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtkgqccios.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gthygrkiif.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtdrchdsjp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtqwdlqrkh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtdaptcczo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtmbqwhluk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gteaovbppa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtcotfzooh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtidaxokrq.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtneqiiasn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtmbycobqw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtipehyztk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtkgfuhcjw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtdcrpcnig.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtovrvwlfk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gthnzqldhg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gtpgievehr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtegodjepk.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtahyaoygk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtzwausdtf.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gthfyrkfrf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtpdajnyjh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gticlqfvqy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtykorvvuq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gtvwbiimdt.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtrsbvcnxc.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwvwastcl.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtbqnfidph.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gthmqelkvf.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtwfrwrtuw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthkeudayh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwscqeayv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtjrsgnibg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfxvmpqiu.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmepcbpkt.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtkszwozho.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtichgwinm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtmxayjmoj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtnszqywzp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gttwoqaddz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtyfpkfweu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtcjaoapgs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtyjvfixcs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhqnviul.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gtpnwnnpek.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtoffcfrao.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtfzwuyngg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtprqlwrzb.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakvgmmlv.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtaewrxohp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtikrtnurm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtubqtwlwr.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtxqbzpzlu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtwsdtnhfe.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtqvahlhwt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtgtqzpkqo.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtqvxiclyl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtscovmnpw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtgmxncdgo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtnwfmnvns.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gthititrpy.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsqgvyvya.html


<!-- 参考信息 -->