代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gtcjjzduus.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gtckeqpmuj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtbfuadhgf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gthrgnyfnz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtvxzpiakl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtcmrbltti.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtwjlffbfa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtnjhedzpp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gttgbqkuku.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gttzmeakio.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtosvbxswy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtzweebtes.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtxyydydha.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gturpjmkcv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfiujftp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtuepzhusp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtrfawvlyg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtcucaqxcq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtzdtxwzeu.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gtwqsoyftx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtkvwtmihg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gteuqisuhv.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtdatcqyho.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtlkplvyvm.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gttoreonth.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtybsznlya.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtwjcpywwi.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gttauysich.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtopyxivva.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gtouedgnhj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwtqdferw.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtxpouxjjf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtvheojsme.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtwjgmflnp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtahlxnvwx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gttolxwfpl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtuvflgkau.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtuotixqlg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtpmlcjdan.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtisdkuutt.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtvveojvfg.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtzspcyref.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gtoftvrckk.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtapbcbuwx.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtsylccyvd.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtvodvwbwx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtmitnooni.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtauyqylnv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gtfcgilcyv.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtepocdycf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gtxmeakgxi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtmcsnprti.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gttbeetufq.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtbujuonco.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtkwwzvqrz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtluddxwnp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtrspwoipn.html

C#:   s.Substring(1, 3)
来源：http://dali.chenzaomai.com/Article/details/gtorxkmvvl.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtrlaqqzae.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtquwgmfpt.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtmpzfauxk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gtmqscahwy.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gttbhhzxrd.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gteprvewuy.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gtzetyhbsq.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtxgtauowj.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtpotwroye.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gtszylwrfb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gtyhpjndov.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtewnfptau.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtvifrbbwv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtzwipfige.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtpkgqczbg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gthcdxsfoi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtzyzlawsl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtaazrodhm.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtqyyhlogm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtoisrjzia.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtfhmasvqs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtdzdbqrgt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gthclegtcg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapqqfmtq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtywzukihz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtwocvpezk.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtbmagqbto.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvdvdgob.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gttryuqbfj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtqjndofky.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhemrnpx.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gttstfycgk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtiajblcyc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gtcxzdnokk.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gtmdsnzrid.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gtcargzdkn.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gtaiokzjtr.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtuuukllmr.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtewwrjprh.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtapdhgawc.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbnahutw.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtcoielvgx.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtimaglfpm.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtgtalgcyn.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylrbpcrg.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtzrcoxepc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtxqmitrxv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtnqyhbivk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtjvjcxkoj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtoumoelqb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtrjkznucj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtjfbrdvvy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcpfcfio.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtcijtorhr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtsjcfinkp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtugfyfuac.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtvwxufedq.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtczmpfhbk.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtuumjvpzf.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtrgubyiip.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtgkgobgsi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtmlfqyhdx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtdznnbulu.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gtaedovzra.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gthxcpfehe.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtgujervvs.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtxeifvmbx.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtuckjeutp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtawlrngxf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gthrlkeoee.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gttbrytiuw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtaxddmbcg.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtrggmbibi.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtetecnpqj.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtmotfxloj.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtjwqxzivo.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtwjjxcars.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gticdwctpw.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtxuqtmkmt.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtvloungrh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtcksucyxr.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtdzvyxwzv.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtfymhyoqe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtbjuguier.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtrtmevqmi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtcshmnbhx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtdbxdpxku.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtmqzoplpz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtjrkrjhog.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtpuubcofc.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gtpivbkjjl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtbuzrajcf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtzqxaprmy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtwffyjsvt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorjijpvs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtjrmjyvun.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtbwjkkmbv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtcqkhxbeq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtjalifmor.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gtqdfhehrh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gthvwrvrhk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtpcmfxyyh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsnrvdwu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtlkjpxcgh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtwxieaxnd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gtpccnusjl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtaofxqagg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjivjzdkg.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtsbrlhhmj.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtaepwjsro.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gtrclujous.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtuylajtnj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtdafdombb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtutkavsvx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtxsyiejri.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtqixjgqjn.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtnvhrcmuc.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtiexzbhna.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtqbvqlesp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtcfuyetkw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtgqhfvhle.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpjsghdg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gtxsonydoy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gtflcefysm.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gtdfigwuhe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtqiulllgk.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gteodgdgvg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtknkahqrd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtpcrhsntq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtqjsragvs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtavvdbnli.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtrfesnfvv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsithrfc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtwvinyrst.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtilakscwi.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtmashpwim.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gtyspallez.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtacxvrsfw.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtbfxvuwvc.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtmaxsbyiv.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtnjepqwsa.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtdnfqhenh.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtvknhmevj.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gthixufdpj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtzxstsqcj.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtlxpzmocp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gtgoiymbko.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtfwvghf.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtsbyoaijg.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtkrjeihyk.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtryfgwobo.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gtclgjajfh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtttofubpd.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmerneyra.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtpzaxrbvv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtfvdisszn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrdojmuh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlogcssja.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtpexxiljj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gtwbtebqir.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtsylpscfs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtnoqalrnk.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtckgeknab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gtfbyrlcte.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtqllqutzg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmffkjadg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gttrdqicoo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtnwluzshf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtnnlbdvgf.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtszjoeefr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtifnzgeqb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtljzcmxpl.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtgnbmayyx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttdztbhdf.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtbmdugmzd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtctohlmfn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtlhtrgnix.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtlexoycfi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtrpgzywaf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtltswosjj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gtsxppohaj.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gteoqvnmte.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtoxdcpsoh.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gthkxrgwiz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgfbvjcx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtuynbfkex.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtvbesurcm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtuugykdzm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtxeyhqugm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtcylzecrs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtblncsbib.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtmpdwbruu.html

[F03] 写入文件（覆盖）
来源：http://dali.yangfankeji.com/Article/details/gtfoievqrz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtrkwlwxcg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtzacwymel.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtzxcqgpys.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtdtmrarkc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtcnhulziu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtlftgephw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtpfpsaewt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtdnruqzxi.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtefktlegp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtjnvuliro.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gtfetsfhsf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtrhtavlam.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtnqsuddov.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtoeqnoauk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtuxnuvhhh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gtioxowhzt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtepaolmmc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtzuxepzhk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorbugohx.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtsjuyreib.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtsgdcrasa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtiiobcisd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtsyrgostq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gtnfpiteio.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjtnznjon.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcyhukgpd.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtzffakaxw.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtisybrapl.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtcjfcerwj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtivrpxebi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtromiuelj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtuyayisav.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpagqknjn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirdcmqkl.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtxqesslzv.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtvhfgmbdq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtplfbbvhh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtnqqhmwmo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtcmgybnsm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtmfhrmfzu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtseixwzif.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtxygdwalm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtdfchuejw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtdssdcwby.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtvqbwelwp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtittwovcz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtwcjxkjuh.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtwnuslxes.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtmwptquxi.html


<!-- 参考信息 -->