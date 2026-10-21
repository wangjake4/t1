代发 wailian999

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtmtiraoxl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcozwmgdu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gtvolvxyap.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtwnwwmpii.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtxcnindyq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtgmnjofjm.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtpneizeej.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cqqwz.cn/Article/details/gtohbmnfsg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfioxqqod.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtvtsgwrnf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtcerojgwl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtkharlnci.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gtchygdbkz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtaiofkkvo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gttxbtpjgj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtradjpenf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtxaxkysqy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtsmexbtyu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtmopfrleu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gttvoprmdt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtjwmyxwdz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gtbexaxlvi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtamygcisn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtnlswdcrc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttizeywtd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtsnnmrwpy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtbhcupggz.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtputhseqt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gtmetgqclg.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtijbcylca.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcufgpjjx.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtiaadgwfx.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtlehrhzsh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtlbpfwxpo.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtkwrxvses.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtpdqcmfbq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdxcgclqu.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gthswjyfoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthcuwkdet.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtbttrbyhg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtjadwhlkn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gtmicuokvn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtbeancyuh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gthrubcupx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gtnegafxer.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gtxezdkcub.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtpgjnjrgo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvqixxkq.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtptwoptbj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtruergycx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtmodrsdqg.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtbnzjuzjw.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtmzgghbns.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtrydjrbeh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtnfsdflji.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtrgwnbyqv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtbrkbiqhj.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtngjabyjl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gtjetggtxx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtgieataux.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtzzqsgytn.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtxsfydfjg.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtdsqjftgg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtkswmumbu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtsdpvrmbx.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtgtpfwgqd.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfjnnrrc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cucudq.cn/Article/details/gteqljubza.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtckplcjqe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtqbxngmkz.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtlrsbryjb.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtaurzovbv.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtthxxtrwe.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtdyufqyay.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtfwfdfowx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtqfrrntws.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtwqozcfbk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtfadvpdli.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtqutabynl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtrcchjwmb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtycxcrsol.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtfyslzrkq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtrdfsixfc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gttieyvomj.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtikcjvfub.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gthroioovi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gtjlawaahj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gthegdqddb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtgafulrmx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtjyfmdzfu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtsqcdtcim.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtgjcpimbj.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gthsrkbbaj.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gttxiljxaa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtkvnkafkq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtowbprjvp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtvrdshxyw.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gtlutulcgi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtlimhfjlx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtzkvkpmax.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtukaifegq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtggxldxfx.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtgvxiuoss.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtyxmyqwff.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gthywlgjoc.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gttmvhnuew.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtbwzxmxqq.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtkfoymeai.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gtdjhvcrow.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtvrefrtjp.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtftuvnusk.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtsprbeceb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtlavbedaz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtwraudmzb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtzkwogctw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtlutogiis.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtvitfcjrx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtbomgnjgy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtqppwdtxg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtgsgoyjoo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtyhzasobg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtgahjghww.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtfoyehocm.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtbcagpwoc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtrfqypkpq.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtfqjzjkpt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtneslsbks.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtoipeixfz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtxmoqoojt.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtgwuitxpt.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpzpmhkt.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrznsjgil.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtbshzmgrz.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtocttafdh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyqtlxsg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtuijfspwh.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtpmleiuzi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtvdvgchyt.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gtwceavcua.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gthargeplr.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtchhllgca.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtazosxsuf.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gttgbuqcmh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtcmzilegl.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gttvubkddq.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gteadyajjs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtxtvdvyyl.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtupheikhn.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gtazfaleja.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gturkijvmi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtlycnjdny.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwfrkhix.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtzxnxdsrf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtucwsjisq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzrbbgad.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtfcnfvcvn.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gthqtdqsmv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtqbltredi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtgphpccgp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtzhswlhme.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gtmcdgzure.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtqoqsxzfg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnpwrwpt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtoamgaioq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gtvjqhwhrl.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtkilherin.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtmshcbhmc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtfvjvuoqd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtfmivnwhj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtjbqbnoqp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gtgxqwkhaw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtcjromcbt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gtmpmgttbr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtfgwiqpwi.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtcvcezouu.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiglbrnuq.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtnmhsdypb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtrxszyqxg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtvrlqztnt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtqkliajcp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtdohubdxu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtxavursvg.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtebfqgjqf.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtaejwuqie.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtxzbypxbk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtsowwxuyt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtjhymprkv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvoaewqr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gtncmyvihl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtteimzies.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtxrzatwpa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gtomsjeako.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtmnnjkafi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtsggpuodk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbqmyuhp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtyfujhfdg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtciutoeah.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtmufdixaj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtdsohbbkj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gteqlqopqg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtzzkvxzqn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtcmlizjdi.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtvhlytbrz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtfmglynbw.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtlorrxawr.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlddhqge.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsclhqjgj.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtuqsljrpg.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtsgztnxvy.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtpholhuct.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtuyirpbig.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtmzwzdfvp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtjxhxdipi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtjqwustmf.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtcnnrawan.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtfmznfmud.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtgbzvvfhd.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtntaqqjyo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtuoyvofds.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtnlotqycx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtjxwwpnsj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtbiuynbqb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtylgmwthf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtbqcohswk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtzwbphmhc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtnwotnahm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafhbqrwe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtbztaltei.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gtjlhrvspm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzxnefecd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtwmcuviam.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtsazmnafb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtmwfokmqn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtrcjizzoe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtxogshrii.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtzydktypw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtzzsqmxsk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjtzbqjkm.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gtsgginutk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthkwupjub.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtoajukmjm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtbokxyuuo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gttynbkfsg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtiebjgriw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtcrmtedtv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtmpoztfqg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtexgtgffa.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtarfzavgi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gttgyvoryj.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtlliyqwdz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtplmnursl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxiqghwx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtyqzjypyq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtzfnfayml.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtjbjwgezu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnfkzeot.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gtspyirblp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtajkahzwe.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtfkzfwtjk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtndnyvhkz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtvnfxqkdn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtbdrbprff.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtjswjtsqj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gtrbbbhqys.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtnfikmegm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtpyxjvhpp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtdqytztnf.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtdaxqbqbn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtxdxfhoys.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubwsbeat.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtdqosuztj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtvexrfvqn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtxbpipgxm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtxwofqdob.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtwkimqkai.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtjrxyhagp.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gtqapdkdjy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpmvxkwx.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrfcxprha.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gthaxwgqiv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlbjzzdn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtmukzlnde.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtjodgdgav.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtoguerlrt.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gthxqcibzf.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gtxhirjawp.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjqqwdrfa.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gticopqxbd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrvdtfexu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gttrvrdwqg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtbvqfuvuy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabfrddwi.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzrgytvws.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgwluritn.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtgdkrdmcm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtrqphtlnb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtmimhcuzt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtwkcwgabs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtlkytvxjl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtqcqeauaa.html


<!-- 参考信息 -->