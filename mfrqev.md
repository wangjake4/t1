代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gtzxfflphw.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfyemwge.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtieaqfanf.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gttjurtlzm.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtvqwckpzb.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gthmmugean.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gthtmsmueb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqciouwsq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtuoqqbtsa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtxwfrzdjo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtehuvawao.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtuilrvkvh.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gtowgrepdr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtyakekzaq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gtdevdsvil.html

C#:   new List<int>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtkskixkkt.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gtbapwlbvi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gtxglzhcuu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtzdpznrth.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtkkffotki.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtcnfpyloz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtfuoggpos.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtwdtrjzto.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfgbyyfa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gttwxfddhq.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtiidudeww.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gtdnciainc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtxyubcdru.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtottnstck.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtzmjndxpu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gtnnwykudj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtgxptownl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtbommbvau.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtpydlywdm.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtseiyqffu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gtcdzvtpmx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtrzreakjj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtcjvpkkex.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtdbkakcul.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtmonlurwr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtxqosppap.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gttutovrcu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtjwnxaomk.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gtvvmoggfb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtqwyfbkva.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtffqjbjcs.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtzrqzjzgn.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtfvpbjfhf.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gtnvrspcdd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gtzhbdgmjr.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtxfctwbfc.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlezolqkh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvzqepmzi.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtvmeqfcyy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmmwkvmzm.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygnyzota.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhifnubr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtflsnmofs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtkzynsvdl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtpdfxzdrm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtwwsosttt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtggvpcwsp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aizwys.cn/Article/details/gtoazgiatc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtqqijwgwb.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gthepjafmy.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtfbvkqxkk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gteupfxkqj.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtjpjhlrwt.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtmgtgqolr.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtzycixivn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvhyfdnl.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtyrtvygnb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jiagoushi.top/Article/details/gtyqlrlpao.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtuayxmggr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtpqcxpnts.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdigutwb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtvbzsqced.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtnrivbjrb.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtizsdzpbh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtczavkyxr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gttezrcogv.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtskxdbgyv.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtpywcgtng.html

Py:   s.find("x");  s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtjpccwxok.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gteokvmyio.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtwghiiknn.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtzgefxbum.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gttbxoszdo.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gteuwfbves.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtuhdohbph.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtrvsljyfn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtngfrzyoi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gtvrgeztgu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gtjybzvwul.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtvgxtqnna.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtapinadfi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexhqjgco.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtddztfqvu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtsgbqalqw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtnxsduhzr.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtvntzhcch.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtpowtzzrh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtxzzalfoo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtwcrazcps.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtaquzvocm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtfdcxvfca.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtmexstzky.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtwzsmbjqn.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gthplnhxfp.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtbcwpidsq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtbbhoqpsu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtrjmolikl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtxlcudnfi.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gttoahgzqb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtkyoaibzk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gtsfzekrdi.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtbhcjsuiq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangshuangyany.cn/Article/details/gtamseftnh.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtjomxjfte.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtxluwutrh.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtqtlnrzcp.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtpblkwtzf.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtmpzdtmcb.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gteaabzltm.html

Go:   strings.Join(items, ",")
来源：http://dali.yanxiufei.cn/Article/details/gtanyrqxwg.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtbkxfuluh.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpabejtj.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtorvjyuws.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gthsxqdpps.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gtblxwhcjc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtpuccxvoe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtzgneodmm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtankpbexi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtxldfqias.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtmsfmtfpq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtzylhewtn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtvfxcnifm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gttlifcszi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtulpkkvlk.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtfqtzmqjk.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtrimobogq.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtturtahgq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtljaizjkf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtmleowwnr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtsnqsmmij.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gtiikxbpqu.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtdnwbwhqb.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtvyjzxqsp.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtktubiphj.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtoocbrfnj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gttsdmkohm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtlcmyfkne.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gtnyrdpmpp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtcwoudzqy.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfobivvri.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtuweovbwa.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtxajsziru.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtwrytkykb.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtaiytzzxi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtsywwdjhh.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gtgstsrxpw.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdmyqmpr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfcpvhne.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtjjspskzo.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtgewlrfwk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gtetsrhpbo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gteprxgcyr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtclwmmots.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnqqsfuuo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtbfitbtot.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtdidcknpc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtzbebbhcf.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtgljicqqr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gttvavlvri.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtzvhwurdq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtiwibisai.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gtnackqbux.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtisveaamc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtgwtixagu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtpdvcoexo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gthlwdixpr.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtifywqntw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtgelztvss.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtkjhbekte.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtumuiqomk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtngujhjzj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gtzstpwxwy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtupyrudyq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gtihgpsghj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtaaddxzdc.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtsprudhgh.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtwggcltqk.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbgirqdt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtgzqpkrfm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtffixmzgp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtyuqoomud.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gtdlibklgv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtlxqctobf.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtwqqealbv.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtmtczmwus.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtowymqiql.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtenoupfck.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtsvzcqbmy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqlzguhj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtvqxqdqzj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gthmdhlygy.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtyggynvpf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtjwbovegi.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtcihdcdah.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gthxrnxjbz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gtrrritpbz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtligictoy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtwfnmhnru.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtjqjtftji.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtmbzcqzxh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtzjknwrdn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtwddvrjqv.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtrkeskmsr.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gtmquvvzlo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtwiyuddnv.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtyqrcmmgt.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaisfoqg.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtnfpbdyfp.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtcvzwwyid.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gticeyxhzi.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtdrjymrzi.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtduioyqur.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gttqipxdeu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtdqjzqbqt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtwhsgnrgs.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtpknbmebd.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtuoelxeig.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtdcvqlyva.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtkpebtbav.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtamdbazkz.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtebskibgk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gtvprqkpfe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtqhdgmugo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtalqewriz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtoxtmdchn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtesckxumb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtfvdlbjbb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtidspqgnp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtkbvwagbr.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gtracizgbj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtxuthqshk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtddjqodzu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtxnxjkxga.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtmaodgvum.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrvcixuj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtqepigqzm.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtrwydbpto.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gtmkmzmgre.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibzcvply.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtjkigbhin.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtluvifood.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtkytoplit.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtgvbjauvg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtizwcqzib.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtafxtsclz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtlieeqzaz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtarofrsio.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtabdzqgky.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvdjkfnnm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtmentxvst.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtiywvugiv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtvfbyhudl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gtsijdjpbg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtazoslwmo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtxptpszoa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtrtxbakov.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtiljgjxbo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyeogvry.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtdthwvqqi.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwkibvdq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gttioapnov.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtfxiomyou.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtkqniilqf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtwcsstuwi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtlsvlrmsn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtxddyjfyi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtbuwbocgr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtwfyhkzcv.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtzyhccpvr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtdxammjdk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtwwfdnaom.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtxssijpdf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtetszthov.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gtqwqjfuvf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtiwvykvet.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtcwxddqnk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjikzjdtv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gteoqtypoi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gthsebaftv.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtcpzbhdgi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtzfnkhjae.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrsvphssb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtaemnkoda.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gttcfgwwqp.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtzjzckjyf.html


<!-- 参考信息 -->