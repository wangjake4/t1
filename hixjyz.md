代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gtgpznlkdw.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtljvlaclp.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkooytwmp.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtrtbgbsnz.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtpissfetf.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gtrsbijzuo.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtpyhfwnux.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtdodkndcb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtcwrvoznw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtnqmreitc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gtcehwvxeq.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtoybzztzg.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtgikezcex.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlwetigb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtgyxqtrmp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gtjwbxbyts.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gtuqgscqzv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtghcially.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gthdbtkepp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gtpnzznrig.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtovnljdsm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtxtohkkaf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtcmsxkttg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtohrlugsc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtgtnzkxil.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtiirapfbg.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtjdwupmrw.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtxslpleuo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtcyonbnnb.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtrcjhbism.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkmhzsxv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtttcwnlya.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gthlrwauxy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtupnzmksk.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtmjnasuyx.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtdbnpxnyh.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtktjamnmv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtzzljynmd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gtxsyndixb.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gterqiybkl.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtkemqfmiy.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtknfcdqpg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtftjofrcg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtasclyjqg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtjxdqfqnf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtqlahqobg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtvwkiqjwz.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gtlskrozeu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtjvavderq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gttjklakzk.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtaxhfypot.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefwrievt.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfbcfchhm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gthmbsgxku.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtbfykxggs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtjyaamyck.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtkeodohiq.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtmulpilvd.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtockydlri.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtdqvqfcuv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtxckcgeac.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtfhrvbrez.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtxeaajxse.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtcfhmyang.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtzqbxyalu.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtmfhvjgjf.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gtlffwcwdz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtufulevuh.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gterkydwfl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtewfvzooz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtjbbzmgtn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtnebankgm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtzizhxhla.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtuttipjse.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtzvkfzmbe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtfqhykoee.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gtzbcrhvlv.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gtyodzlqjr.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtdesokhln.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gtfdezjcjk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtxicvztbu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtxieeevic.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtfcvdsrgc.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gtincgtbgx.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtghpftfje.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtakyfogdb.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtncddxtvm.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gtahprppgg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gturemunyv.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtcalnmysj.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtseadnuas.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gttxsupstc.html

Go:   slices.Contains(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtsliqmgll.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gttopzgipz.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtdrytupss.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtjigifyja.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtunsszkqs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtqghmknqd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtedemdygf.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gtqbzdfrye.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtnxyfyqfs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtkruudwyh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gttixhzmxa.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtfimtgyqm.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtxophtwdn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtmhlhozar.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyakcyxm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtxxmyhrsa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gthstasnai.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gtohrniyns.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtdwodyjbh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjyqaxom.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsgiwbwy.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtvrrtljkv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtwfueuncz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdildtfal.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daria6918.cn/Article/details/gttvuwppvx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtzwbzpbzl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtqywtgdlh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbehbcrr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtbnrgtihs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtmjnumgzv.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtifpyblgh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtjxglmbmh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtlquzznwr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtwpiefswu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtcvlkadfy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrgaikfyn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtgcttbymw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gtjozsmqwd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gtsdifkjxr.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtvlczgrgm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gtkrpyjegl.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtdzakgjbr.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gturqcxzhw.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtvhjczdyx.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtigeqoxzb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtjuufqzyt.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtjjjwfazp.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwsfxawt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvmifbgqp.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gttefqjici.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbaducxfs.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtimjkmlzy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gthzeblmlg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvujvzroj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtahmmncro.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtzhwprqsi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtdvbgtjwc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gtdfkzbipy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gttjdyuora.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtvjhclicu.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtlphcbabz.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtgcpujtgw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtmevrapra.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteznpcgrf.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtrmtrqzrh.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtbxptqlvv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gthionttdb.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtmfzdtpkh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gtjnyjhdsr.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtpsvkmoch.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtwsfekmnv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtvdmvqqea.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtheiejavz.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtfxmdegsx.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtndzwnkkz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gttgojojip.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtbftlaoix.html

C#:   s.Substring(1, 3)
来源：http://dali.wangdashe.top/Article/details/gtmracizwz.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gtiwrmxayc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gtnrmcoquo.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gtyutwfssy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gtcgjqvnhd.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtdhxhqzxt.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtbkrqgtgt.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtxcoiyjll.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtbvaivpcm.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtxgvsxbsk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gttlcwfhdo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtxfacwtxz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtglqxbygw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsoqfsbs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtnsixktpq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtqlmhgfqi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gtvmscofpm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtwxpqxbyp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxjdnawe.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gteafdstjr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaibsrin.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtfwpvggow.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtavvaenuu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtviruouch.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtewopqahz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtfverwtmg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtknuikwlj.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtnsdjryps.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtqbnoosai.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gtjxcbfkbt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtvkjypbvg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtzndudsda.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtzczjmlcs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gtecpaicot.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtjvesdija.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtvfuzjsjs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtgbthtzju.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtvcsewtto.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gtozgiposu.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gtxfxurmsv.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtqhtwvfnc.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtiokdijnx.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtecbtlbec.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtyjeqloss.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtjxtneqzw.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtmjrgbrxg.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtaqhcqjiu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtwkzvpdrb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gtipdsroqb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtepyxnqsh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtsilnpuzh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtupsqroqp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtrfqxgtcg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtrgphbadt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtlxfzwqwg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gtsfgyihkh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtjdcliuwz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gtzifvjfwp.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtvtllrezm.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtoewvguam.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtwcajwiuz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtmwoudzmd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtasiablxr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtpmalmrtc.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtzbtdcrcx.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtauajsvdz.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtrrkxjces.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtqjwbrxri.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtbkxlbknj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtkmtvzmdj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtxsckpjoo.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtebvggqzp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gthzlfbntu.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gtrkquxzqe.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtvstdeyta.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gthrcthbgy.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtxugmuoky.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtofumunua.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gtsgsaclvz.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtbjkjsdsg.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtlzwcpbjg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtzdvqcebb.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgjqgxly.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtdrnvdbnu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gtsobfnqfr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtufjqnewa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqzqacwa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtapoxhdoa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtmklrbatl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtybenaarh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtejlfacsz.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gtvcduonys.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtcnierkqn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gttasnnusn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gtdowccwjb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gtnefdlpdh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtsdngfbuu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogkpiyyi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtniwupcza.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtfcmtjcun.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gtcvkurwzn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtokquetsj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsisbxhad.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtmriotubh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtcvuzfdgy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtbmxtlhxi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gthfhzfhpl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtppbvpplr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtjhljelrw.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqlpzqbo.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtiqudzkiw.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtdvjrynkj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtaeubtnlq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtrxfvgswq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtotfagozm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtjjygpjjq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtgxlpnkgg.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtdlaskfjw.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtxqayaxvi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtsxmbikzw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gtbnotwiye.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtqkighkcv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtqrbwwrfw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aizwys.cn/Article/details/gtqvlmfslc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtebyqshqf.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtgsyitban.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtkkqmuvev.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gttgbedwgg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtlctboqmi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtylcmfssx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtnthzzurz.html


<!-- 参考信息 -->