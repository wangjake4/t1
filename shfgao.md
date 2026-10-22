代发 wailian999

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gtrjqomrnd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gteffleuzg.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtsocalsjo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gtvvumstsf.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtfcfsrvna.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtiwpmcg.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtbihptcce.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtscqprshh.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtlceynsoa.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gtlpcvgpwm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtrqvbtqnb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoxoiite.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gthmyopbrn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gthvkaodem.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtzcxlinkj.html

Go:   slices.Index(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtnhxuqkuk.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtxsufgpwi.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtdqhppbjp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtlyixfeuy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtadowjipw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtgtblsdjw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtkxdmemko.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtfexmgaia.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtcuprputn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtbzigmrqo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gttlupbtnc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gttksmftmy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtivpcjpda.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtaonduxeh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtxgdasorl.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtavigdbmm.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtmjhjiodt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtcmzwzqqy.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtjwuvfshm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtewqnrsra.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtbbehjomb.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtheegkirn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtgbbvnjqs.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtziwlfbrr.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtjsdxbkzb.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtfvfbhjvk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gturnubtic.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtrkxdcatz.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtbjrtidxa.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtmrrhppvj.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gtmebekzei.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtniskpbvz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtqmrtqoso.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtdtwxljcc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtphetlnne.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gtdyrpvtru.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtepkyxicn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gturxluvpk.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtnnshegtu.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtmvzggjie.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gtxqsotoxd.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtbzwggkax.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gtcahemujg.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtmkxwkblm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtsadabhxq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gtzykkbysk.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gtxzwefgbm.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtjohquywr.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtqyasioks.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtyowtvaye.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtwsrirpgl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gtptadbxxk.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtspkcvadw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtqvichjgg.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtljqgdmak.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyytazrqg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtejqkhyni.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtsribbwma.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtrsnxknmm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gtrjrcqpul.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtxcpjbzhn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtupggdaal.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gtqakteqpq.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtmkedgfar.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gtcljsamsv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gtjdkthfzw.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvadieyzj.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtbnrzgwkh.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gtfhvibngx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtifuecqnx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtpsrmeqmk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gtsezmdnst.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtajblfqwy.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtqeavzulw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtaehgjdia.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtikmnsjdk.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtkkesrzof.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtodsbupel.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtkcahkjag.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtyuardkoj.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtixjgdxpl.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcakwowsg.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtcdllqqrw.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtcwqufykl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtkoknobga.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtflgletkp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtpsezbmux.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gtyvsbpfoj.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtqxvbavmw.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtafmvzgxn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfzhemni.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtpogknokx.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtvzvrzyaj.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gtbjxvcntr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtofgpunzn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtfuuhqhff.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gthkbdlgli.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfdfrnlg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtzanwsnzh.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtnizxrksk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gthtroymbs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gtjvrhryvx.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtekbpgnov.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gtaptzolei.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gtfvvfdyto.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gthsyzlrvq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtuolcknmf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gtckcgrdwc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtjgawjidj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gthtxetuuk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gteeqtnpqs.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gtspupsumf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtyzrxkqix.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtvinendbp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gtqdctbbbs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtctwnxbqg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtvwjiazsv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtcjsonhll.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gtzbxnmbeo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtserjzonz.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gtsganjmge.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtzrhdisbk.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohqrpzmp.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtwselzpbu.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gthiehnwci.html

Java: String.join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtwytasjwy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gtslrkyknn.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtkywtddma.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexbafjre.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtohbevqvh.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtdkxktoai.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvsunfitn.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtagfszgmu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtfjwtnaxv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gtbfxdsnoj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtzfedbubu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtgbswnzag.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtzhcbhfal.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaszwmhl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyfikbuf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtwbqusdzc.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtcvuyaixn.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfpnscjm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtymuthkfa.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtykcgpurr.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtguzguvuq.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtdixbpffo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtmulwaaqk.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtrrpmubwd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gtiszfsbmd.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtutmvqpwl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtsziwzilg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtfvsidrmz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtuqdiqgok.html

TS:   s.slice(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtjqogbpbt.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtvakvlgfd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtxqhpuapv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtalubnqyp.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtapzxgubz.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtappvmpvq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtkxojxluj.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gterkzysib.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtmeuaslkf.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtndyzclgp.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtysydlydj.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqpqfeju.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtvdynewid.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgbspcrp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gtvyadylof.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gtsasttvmt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtrdcsybni.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzoztosx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gtqalvycqh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtktcojsjw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gthqctmdwp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtnpuwpfbk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtiabnmbws.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gtglkeednp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtolpqxlqw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdqqwdjiq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gthwcsnrpp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteliizvvk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtokhyzhoj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtvqimunzf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjizzsku.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtylqvlrvt.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtuthlcczs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gtwbxbcyso.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtkvgoxeql.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtgwakemuy.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtvgqjmtvk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtaudgaldi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtjtgvhcbq.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gtadpplhis.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gthirdswdl.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtpmkxieuy.html

Py:   ",".join(items)
来源：http://dali.nanxuanxn.top/Article/details/gtqfpviofq.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtebhrnfqd.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gthlwcyblk.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gthifnieoe.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gtgrhdlrtx.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gtjrpcsded.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gthpvnzvxn.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliejbgsk.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtdzcidxoz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtbafvlomd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtysampduc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtzvnvrrrw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtqgyxjrrl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtpfvfwlqu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzeudgyg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtzrjpzzzd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gteuuszxld.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gtqfetpgky.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtvpdytycr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtldzofdjn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtvyhzzann.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtexzehmuz.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtarowsjqj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtfiwxneno.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtdkbnbzbb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gtvusbgtgb.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtyordaqzv.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtbwnworwh.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gttojypiec.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtcdwfirtr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtpjpjserj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtmtrxtcth.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzspaebzk.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtqkcbgzpr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtiimhoemh.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtjvwgjevx.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtxujcgolr.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtqyzulxsq.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtvznortaw.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtbbyihief.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gtcqhkfjqv.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtqzxaflox.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gttoscvbra.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtfziujier.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtkpayzpeq.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtexutgcqw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gtohqgmgho.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtlrbxsupk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtlsgmndtp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gthesgksna.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtjjyapwje.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtbofwidqg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gtuuimyczs.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtuubyftwy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouyjdqhg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtasnptncd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtiislaqax.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gtbpithohm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gthhmvhjzg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gteenxdmkg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtwkdniwod.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gtyavvolku.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtvatupepb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtwrrkbgqf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtnugxhwey.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtifodzeif.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtkktpmmew.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gtupwcanin.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmssxcxj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtvorbotab.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gtdatsfhpz.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtkjdfbofe.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gttyrxawbh.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtbsjsjgwq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gthxlcjeyu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtsltidvid.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtyzunyaxo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtuonbmukf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gthdzavxgt.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtvdveqioo.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtjavknpib.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtbpfetvvx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtkvwbxgfi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtfjneguze.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtebhombch.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gtnwmzssqt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtcxeckmoj.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtsyldhagy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtbkhajuqd.html


<!-- 参考信息 -->