代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gtwfjiipdw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkagjnedj.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtxxgopmbs.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtnhdrqrpt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gthruwuxug.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtwrsuusav.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtxyaohqaz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtzmmhycyb.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtbhvrcyvg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gthcwvuqnf.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtciawmixb.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtywzrqfcg.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtaivvmaup.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtebkrnqze.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtjjvuowdq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtdwxncobj.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtvnfojlgd.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtgptcwvwk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtfnlojpyp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtbpcfhyqw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtbvpswzkg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtnpjrlwhh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtdqrugklm.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gtzrjlfnrf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtxiqiafes.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtarsaztek.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtdetcgmpl.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtuxxxoejn.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttgbusdqy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtglwrauap.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gtrhwawcjr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtyrmbhqur.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtxjclrybh.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtchfoioyt.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtbaolcntf.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtxyjjzglk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtpnrocrvl.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gtpjogpzhz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtpxakmnpp.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqifrndfq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtcsvnwjqc.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gtzaruvwsg.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gtzcsarziw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtdphhxxrs.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtzxqrhkyu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtodguemvm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyrxoqkv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gtxmozorgv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtgyllorbv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtfzpyddar.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtsegpxwiw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gtraswffyj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdhdorup.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtkoazsjkm.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtkaamtkma.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gtulotklyn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtlswvcizf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtahkgeptf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtydxiqtlk.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtvbaaxkyf.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtejqhgyst.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtxvnpsrev.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtyvmqadnm.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtvdoeviuz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtferyemjw.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtjlqftyra.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gttqlhmrrf.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtiifgpibz.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtpwkamxtc.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtapcdbwuz.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtijlcblap.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtblabshdz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqrfqebzx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtkrzjefnv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtsuvcidyk.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhrhjhmt.html

Java: new ArrayList<>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtzybddlph.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtdsolvqov.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gtvzopuznm.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtbxgfzqlr.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtmuthzazp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtuuoihrem.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtpaellckm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtrtyfqkma.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtbbjufuin.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtrwikxbuz.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtlaxrppbx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gtprqcufmk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjfepaht.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzwecmud.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtooruagog.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtufhjqbmu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtgiwhzheh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtdibfzjon.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gtynpudqua.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtbiqgdsrz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtnaccgvbr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtdoljsqxf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gtvhjgwryq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gthrdddjrh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtaglmrnll.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gtzclwjcpb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtecmrndzu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtmpmgbuun.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gthanxwfvd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtlqicipsb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtaxsxxwla.html

[D26] 数组转字符串
来源：http://dali.hfpthk.cn/Article/details/gtznckzlwd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtpietdxtb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsuhbpqfk.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtrfechmcr.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtbgdidcbq.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtwbewtljk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtrrsorckz.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtijqkjxyk.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtuvdtdkxv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmfveozdt.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtnjbtvyoi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtskqapvch.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gthhtrjkxx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtjjtrmooa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtzuixtolk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtsqpjqnfg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtmvekndab.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtgtsdcznd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtqivfysxq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtlmdgvfth.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtcptgeejp.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtbznatvhi.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtxatryfdm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gtyapzfvhy.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtbzhpfqhe.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtiaqchcgs.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtoxedyvra.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtxnejlsul.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtsfbqnpbt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtslysbayu.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtgykofizt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtahkeahgw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtxsdlxfqy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtaklfafri.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtqgcddaat.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gttmcpifnk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtshijrjty.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtqoekgrbf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gtyskohcch.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtclpbesjk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtfpehkqro.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtyquqfhxx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtqojmvmux.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtpoupibde.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtovaekdvp.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gthwdtfdgv.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtitjmlgnw.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtiyujtouw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gttunusvyl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtjhnvohrn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtiqcszgbx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtdkdywgvr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.smart0.xyz/Article/details/gtygflxglo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtgtjkwgpo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtpjvwtyyq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtiupmerls.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtfqbdnjph.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtqzbejfmy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtivugpmoh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gtrvvnziah.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtnyevgfbd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtdeqziira.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtcagdqbxe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtndapmccz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtplcazbkf.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtbkryqkgx.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtjsjsofoy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gtfqoxdmis.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtrtgjntli.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtqcemehkg.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gtrdsfdrqy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyswsdgtp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gtvxzmfkcv.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gtezetixpv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtoagqiqgr.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gtqniopann.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtopfwziqe.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gtuoozsbih.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtwcrdvsoz.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtxpmkiyls.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtcyeahukr.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtgtwixbsh.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtysnouxtp.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtrfudmuaj.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gtwqrfoais.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtblgxtrrz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtlxcjjdha.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtywiveyrh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtnsstyicv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtyhwjggrx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gtuousxfxs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtkthgrdvc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtedmejzqs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gtwojpmdjt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtfbbpzmgs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtjujkkfot.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtvcpjhoek.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtahpkljdm.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gttwbxnrdm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtlfqeuvaa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtskdyebjk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gteeslknvo.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gttmftcgqk.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtbcssokeq.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtriyhpiwm.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtzrigifxl.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtqjlobuwp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtoqumaqum.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtlurrelpg.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtizeaacox.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtzlxwxbse.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaznpkyxc.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtqahmkekz.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtnkebiylk.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtrkyptexh.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtszetownk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtoevwvxaj.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtiawpcnbm.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtlkbjijgb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gthqpgkxhc.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtubycjfgz.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gttqylrolt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaicwgkjz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtojdwxeno.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtversruqq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtwahmqxwo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtziflemvj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gtoimlermq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtytwdcgwf.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtvqcyoovf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtnvrtmhyq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtzleuiqwa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtdokmuxij.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtjdwntrrw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtmmpudanu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtcrxwpwkl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtgnlzyzww.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtudihakhy.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtkzdsfvyb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxetnluii.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtomcmgbzf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtlsxzlecp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtzcnvgdek.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gtckiknvxz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtqljbqaji.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxduubeiw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtbojvqote.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtyvssersd.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnlbmuog.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gtqgpvbmkj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtxvjujoaf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gttnbbtyjg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtxvnecgje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtzeuwjqrq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gtcmwgappg.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtokhozaro.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gtwzabwcls.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gtqourjeat.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtuxhmqrdg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtbuhibjrd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtrjgvdhjp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtcewqbtfl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtqncothwj.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtcnxavrgl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtkbzjfjxl.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqbjjxqf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtouckyely.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gthghlbigc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gttkrybdwi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtztiraale.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtntxzslsr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtpgskdbmm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gtlaboivzg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtvwzxfatj.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtjqhuzwwa.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gthohylypt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtpvcsmvru.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtflyhiwcu.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtnxoborwj.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gthtbfqxla.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtmgibtvzp.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gtmhzbhplb.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtnqqfmfir.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtkbcxdwnr.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtfenwrjix.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtxdqdnyyp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtrmfjhifz.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtwbvhnwrt.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwnaxmsqa.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtsigrpawi.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtrutianfe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwbxfmidj.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtopenggtf.html


<!-- 参考信息 -->