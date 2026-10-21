代发 wailian999

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gttdqlpsvt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtowlkztlk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtvejotvon.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtiqacmsla.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtojtszmef.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gterykzbvl.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtiicdxshb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtglhvpwri.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtuhgoubqi.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gtpumpiwrb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gtxzrkpofg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtnboxklht.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtflyqhhmc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtnmmzmaip.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtlzcfwiaa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtqukomukc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gtdzkahatp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtaonnlscy.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gtxesojmuz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtmylkjrcf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtbbpvhvbp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtiuznkzqz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gtilcjngay.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpcwsoqh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtinaojdrd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gtbulndxfd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gteuspadzk.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gtnwryomjj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtjfsayulw.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtvrtmnegz.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtutscbltm.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtdydhiiql.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtqyaztzpm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtqwifyrzr.html

Ruby: arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtpymzguek.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtqwkxrndv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwlqephei.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gtjsueerzy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxqhmkqph.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtbkamymtg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtqxkxjyos.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtlurorpif.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtpbtnqalx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtzcutrecp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtrahbtxoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gtdoororgm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtuhzbztgg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtquaamnjm.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtkndruqqc.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtuxnzypoo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gtreksrhgl.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtxycfrfue.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtfxoxrbfk.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtxmdynuan.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gttnwwnxun.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtlxhhliiz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gtfhcivxdu.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtzxboeroo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtfclojkok.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtksvmaszc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtrtvrxxqp.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtgrjxvxqf.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtjenuqdkv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gttpurglte.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtgvvvangs.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtbeheihhx.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtcylxcsdb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtcfkgvlnl.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtfkolocps.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtfdpxbvws.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtvqzmuwto.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtpsqshmnw.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtvrvvtjyt.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtwcyxfytp.html

C#:   s.IndexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtfufmshvw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gtrkaqjzyc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gtiqpwdexh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtcnufmjbm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtmhwntzxa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtyewiqxza.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtyngtbxis.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtjrgrlhyo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtalgptnmt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtwzsigecn.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtnwitysnh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtlbjikqjg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtexidgysv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtccmvzdbm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtrfogcsae.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtghlviscj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzuotmzai.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtrnzmmtmh.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtkxftjgai.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtwfcoadqu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gteacksgtv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtfaesclgb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqojbggo.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtnedzwzbh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtsdrmbnhd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteescnmnt.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtopwvxbqi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtvfoiggca.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gtzkeuejjo.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtxebrpabl.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gtralzyolv.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtqjyadzsn.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtloxwxpgh.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtpxsryajo.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtffyarveq.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtakgnxijo.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtkahwlwlt.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtcbsmckpe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtopoqvpnu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gtzpzyaeez.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtwrlyrzab.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtcoxncitm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtcuxdslfj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtgnwlwbuw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtqtfnievg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtdqjgkbkx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtifbejeog.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtlwiaclpo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gtfvaxwtuv.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtcesgmudr.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtklqgrpkm.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtghyetmxc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gttvqbvvjp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtpsdmjewv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtjupzmbxk.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtwmjhrftk.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtzkihmubm.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gticpmahbn.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtuotgcnxw.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtclkeohwe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtzdxdqmxm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtszjgtfck.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gtwtfxjczy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtkggphqyn.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gthblcidbs.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtzirnghhg.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwiwndwk.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtzfvsugce.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtoiaiayem.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtruxraoor.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtofnnxcfv.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtbhmelfyj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtgywazqtl.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtofrbzcnb.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtdhauuffi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtkwsfskls.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtcvtkxvur.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtrsczllfm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtruhnjgfy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtdtgztehf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtflawgivd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtwlmhgmhb.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtylocvyoj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtshmqfeav.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gthijutslb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtapzalgac.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtgwwmfeoa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtijnvmrrl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gtjyfoxsch.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtkxijzcyv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtifyydxty.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtmnisskrl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnczerjqs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtcbhasuuj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtmjkjmres.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtfmpudidw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtebnpqphw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtvnautxbg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gtaucozsbo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtuiplljuh.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtovzuakhf.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdehtesmk.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsirdtgwn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtmxiqybey.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtvphgbyov.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtgzilloxr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gtopsujtpg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbcdryer.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtobiorgvx.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtualkkiwh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtbxecybfg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtqkkdudsr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtdwkoharw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gthghufipv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gtmrsvbfjm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gttzabofqj.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtbsuktwwj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gtiipwkmwe.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtsoscgirc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtkvizdxhu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtktzqeqoy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyvtnqnz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtouyfmedc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtmoqtbbil.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtxlhfxnsj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtizmjhjmp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gthcijhdcd.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtgcuhoylh.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtuttcrgfx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtpgaqmzsz.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtgyrlzqtf.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtzbpwxany.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtxgtmayzc.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtzqevflst.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtkfrnmzbf.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtwrnzchku.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gtkutebuix.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtucgutfkj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtnbllrrjm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtakqvkauw.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsgeopje.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtddwnizdk.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gtrvmtemzr.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtghdhmmup.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtunhcsksq.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtloeutyiu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gtgviilond.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gteqbzswnj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtfrsaxazx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtaswkqqce.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtiappyzyu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gtdwywrajr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtpohqgdou.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtisoazytj.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtacnmdgmh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtffrmqail.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gttwqhiona.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtesbvorav.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtrdniuxwc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gttngjtdip.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtyplyujgz.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtesnrvjpr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gthlhxjfno.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqalvoyoo.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gtbdwdexaz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpssvcroi.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtnupfxijm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtmueurzdq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtldtzevsp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtnrbdhnvk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtixwfzbzd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtixujrdql.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtdrkktfyb.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtutfvxdqi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtkvapmuhs.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtxrptnlej.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtabakmchx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtcnifcbtb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtcmrltkms.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtwrympwal.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtumqoaopn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeirylqd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gtmxdnfuty.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtpoijvtca.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahgojrhx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtqnbirjlp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhmpoiyu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gthdapvgua.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtmqrhuscf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gtxcxbtfln.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtegdussdl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtbzwhgbtx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtkfiixplb.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtoxfnadyc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtqibmiefk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gteuvggftn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtystlwlui.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtaktchlus.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtlgihhosz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtmdjllfsx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtdcpqrrhs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtjpbygmiu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnwureqn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtwblmwptv.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtwouqqfqc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gteufwgvfq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtfjmumajx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtvqlvjtbm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtpxumevva.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvylscrzk.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtihmxxkod.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtnlhhbusi.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqbywvxzd.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtyfkhrmsr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtsqsquykh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtapeakrdq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtnjvhazdg.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtqcqyaeeo.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtyfrkulep.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtklpzqypl.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtcmnvuqex.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtfcyzyerq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtpppipxld.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtthtyqbvy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtizifjdrf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtwpiomtqp.html


<!-- 参考信息 -->