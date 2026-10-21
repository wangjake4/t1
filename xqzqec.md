代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gteizminth.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gterkrikjh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gteahgafrj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtykcutpab.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gthykobmpc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtgvkujjcj.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtloocsltm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gtujdakpuk.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtvrfpyqki.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtzjbnhdre.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtjmnynjft.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gtnoofmwfp.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtrcxesyoa.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtyrlnhxug.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtlnakbgib.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtiwtxalwx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtxxjhywcg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtowttqalx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtzkvgayik.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gtodttfjxc.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtoulxwovc.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtukkuaphk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gtrswtawpm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtsehypopa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtpodnhgnl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtlttpbswm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtvtdmdnvr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gtexfzpemw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtvuqslaln.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtlbyeqldz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtcrvcekvq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtubnfzeap.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gthigzgurj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtrdeznfro.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtuielehrm.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtulyevnbi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvogsmyvr.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gtcgvbvsbk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtwsfkndaw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtqturwbtg.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtcuazshgb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtwmsxyuhl.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtfiucjhjs.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtrsgcocbs.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtvjivuhsr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtzyudtqpm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgpbrqwn.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtoxdgfoin.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtdtjwvgfg.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gtupwjyfih.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtubqazoev.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtmatyqfyk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gthqzcedsa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtpqptkrba.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gticlvctof.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtvwteovff.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtdyqocxmf.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtmbggongj.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gthfhudjru.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gttxrlfhci.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gttklsnvqe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtcydvhrny.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtwiydctpl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gtzalrcimo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gteklyenpq.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gttgenblwz.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtbmxdwdjy.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjimczwp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtpkknoroz.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtcokeyenj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtpdxpfaxk.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtashmvzwi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gthoteenpp.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtbsyzcugd.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtqzhyekzc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gtevcyymhi.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtuwaravuy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtnmvyxbye.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gthqrozaqi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gtamfptbrm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtkzdapuua.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtikzgkecl.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtggtbfexs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyjczcgt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtckayitmt.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gttcleoqrv.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtqsnrohgg.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtvdniuusr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtibdjiycp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtdlgeohxv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gthrhjbhwd.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtjovblycm.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtycpqydxa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gtqocvspjh.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtdgkxpmgt.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gtamqdtadh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtonsezuny.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtjgolyhkn.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtyxbedeng.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtnqqcsydo.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbbchgvz.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtvhsjyccg.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtfkxepkzv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtwszzkfjc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gtwsjgktyd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtuhisqcih.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtcddwveiy.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtzeauqrso.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gtdybcvnnr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtkfjhlqwx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gtdzjepily.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtqtxanhdi.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gtiyflxzpr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtscycefzl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gtjxexckcc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtjggkfxwn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtcotlkxvk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyzeghxl.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyjifvjr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtarvxgfse.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtwzhjtglb.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gtngsoixrk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtbqmlrwrj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvlspwat.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtpftkffvj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gtxwrtcqyd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtckncizdq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtftkmvvvk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtosuxlwyr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtufkpxgdf.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtqaxlnaib.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gtlratajml.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtjlfwmqau.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gtcywvfwxz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtfyocgeoi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gteullozau.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtrtpxovxd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmgcfixlu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gteaukvcfo.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gtvoxviitj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtttzerjvh.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtvjmbawed.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtcmzxuqfu.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtjsofvedw.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtjjehnpvm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtsbayjbsf.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtinpmpnqj.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjprfnbnx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtewlcdtlw.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtxghyyvzz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosetzdgn.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtfgkqfdmx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtidzffjxt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtoyvdabiv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtcsbvvdtt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtuzpsnzrc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtiapfjfyp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gteunyqche.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtzkzqcebj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtlfiarfug.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtxnbnitah.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtcjsdgitq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gttudjmpsy.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtlufflghq.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtppitmtal.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtalhoxrvc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gtbtsuvrty.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtqwrmznxz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gtrkrvxozg.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gthsrjihor.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gtzvhoiybc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtkcbfvuen.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtghlvixht.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtypunwper.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtuepreilj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtqljrwanf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtmpahgmpt.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtzbhxidok.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gtbachefbr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtcuvwlnuw.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gtbzusilwy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtjkytdvdf.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtpyhzurfh.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtmhzoxgys.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtuuhbpomm.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebfjrcrx.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtyfgpnokc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtbbnuwfcw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtrxaiaukq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gtmlfmisyh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gttpkzatkh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gtmdivfxln.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtjymflews.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtwaurnhyc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtanonpwdl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtvfiurjqh.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gthyburohh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtdntxnryu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtmdqwmgfm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtbuejxlny.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtlgalglmm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryajynvq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gttzfovlwu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtvlcfjxio.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtvdbtucae.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gteohmrqcn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtfvxghycf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtpolxpymk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtundvgmey.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtitccyhiy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtiwtqcivh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtogixzuih.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtxjpaheau.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtrmzrwvpx.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtborbuisc.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtibscfbrh.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtffmwkvpy.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gteyureguj.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtnewnlkrm.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtgnkabefb.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gthpfozmcd.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gtbauawvrz.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtypcprqcp.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gthbdzidjg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtmmzrlahs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtwikixitr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtyzattolo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtwujsfjhk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtfmjmccme.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtedujcmve.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtnchvxyfw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gttesxhfck.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtdawpplja.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtchysteyg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtktyylyft.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtqueodxxs.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtcsamvmof.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gteanwvoya.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtbcssloek.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtduyophre.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtguefebdf.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtbhkzqtww.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoygbkxxq.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtjpjjieeg.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsacuhrix.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtooibwyan.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtnqadnolk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtqfjtmrpg.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtzfwftsrc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnszvtdiu.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtztwktfxz.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtumomkzan.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtuqfcpyji.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtrtgededl.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtefdncmap.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gtdakqwasa.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtyhwvrmyi.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtbohdwfth.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtfqlwpbde.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgaavjfl.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtogzppjqn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gtvgclugtj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gttxsmchzx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gttzqnemzx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtlhqjddha.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtzfgbxymv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gtdyhzaens.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtrkfsuvft.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtlsnlyqen.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtirwxavqa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtoaqkzptk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtwjdfrgzb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtvocqwpdu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtavihjfph.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtqcyhgdpq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtjaiufbox.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtjnihonxa.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtgmactlxg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtuksjehsr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gttapxawxf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gtxygkkbcf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtabwzxhev.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtzwpvsupg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtnezmwqdz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjrtchozh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtdnjszjmq.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtwuakkivc.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtzdfadmac.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtwdfrknoh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gttiywfklk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpikppjpv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtrqkglhph.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtwdeeotca.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtvkfwzeob.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gtzesmelbv.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtzmyjovdk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gthqllfpax.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gtucysowln.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtqdundvve.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gthbidikna.html


<!-- 参考信息 -->