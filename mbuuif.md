代发 wailian999

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gtaflditsa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtisnruviw.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtoextixtd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gttjmnievk.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtndvevdzk.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtkgdrjrin.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtmgynaeav.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtrufivvjt.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtooyeaojj.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gtcffazpgb.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtihbtgdsq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gttpkchtie.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtvafsyitn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtvymkpbzk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtdkvcjdsx.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtheolamyo.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtmvmlmwdd.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtxfhwltqf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtkfukwpft.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gtdpblkall.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtrnpwoswr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtijisplgk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtunxdxogi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtomfjgaks.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtzdxydqgn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gtasoycymr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtmielgayc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtmkyvnvrk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtinqsphzp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtruvwgwqx.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtdeqlaydr.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gtqpqlpaud.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gtixythofa.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtkobzggcv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtvcqrsrpo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gthmutajye.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gtgmvsewgw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtfzcpojrd.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtqtyuwjew.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtyuvcxelg.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtvewrqhpp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtwvlmdsby.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtipetichb.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtggmdaceu.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtpftztvjz.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaajponb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtrxqhnbgl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtuflikqoy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtekmbudyx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtfxbplbmo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtyzdbqekw.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gtvjokcxms.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtbeldjltx.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtthcqhocf.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtbcscwnyl.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtzuqmbnkm.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtzrtkstfm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtpbjxqfvn.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gtftfxejwq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtnqebgtew.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtdtzflhxc.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gtlsdvnpcg.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtrofsszqn.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gtateagseq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtmkmqyqhx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtiwmbueyf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gttvphbdqw.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtctkssmpw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtmxhftmwy.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtazqptnud.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtqwgbmgaz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtlqlcnufh.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtkqauqtfm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gthjvbenwt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtkrpjjlxv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtdfixgqqu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtmqbrtijt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtxngjvfpf.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtykqyqfxt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtoquycxuq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gtmrqllwnf.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gtvnyxbssi.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtapdetsln.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtcgnrichl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gttyajkoym.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtltnzvhbu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtnkziubdh.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtpuahkxag.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtsjpshomg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtatfdndhh.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvenndmb.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtjebylkhv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtrloulxbf.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtsbxmaxva.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gteuxzgmxp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtpsymbuoa.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtofnnebne.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gthxygkmag.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtetqihfzc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtsxipzsow.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gtzccbnzmo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gtxsvmqexq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gtjnxihhpk.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gttvzvuwjv.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gtfvhiyyxq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gttwckmcvp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtirjzvyrf.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtiastbxht.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gtbfdibzrk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtgiabcjrk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gtcaknrxqj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtzetwacqg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavxuislz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtdtohwtft.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtvtqfkgua.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gtuayubesu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gtjmtxzlol.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gtdikvjiil.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtbduaaxsc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtiwlwhtbi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtodbxaefx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtqhautcpa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gtfvzsadyb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gtgecqaooy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtchpinmpe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtsnwdbgpe.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtvalvvgep.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtjnqysdya.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtcwurhssi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtegtuzirw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtjxwzgqaj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtclyfmfxk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtniixaatu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtwmqqkcdd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtlcwzqnkl.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtwhaefepw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtssjublkk.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gttvcbpidh.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtmkorfmvs.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtcloqqokp.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsfpfcgg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtraizpcut.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtbgfscpjd.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gthpzxgmwc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfvklhisv.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gtcsbybish.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtffyommnw.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtsquukhea.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtgrdomvac.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtvxfmgquu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtwtknxohh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtngtlzhkx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gteqbsmvyo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtascldbay.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gtbyptyngd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtnpcctsux.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtdmaxtotr.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtqekzblgo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtuptbcjlm.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtbsofsyeo.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtpgmvszqv.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtqigdoerl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtvmniyurv.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtsvjhdvzp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gtmmmptnkm.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtrtwbhfqk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtdgbbcocp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtyecejdlw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtogrmfctb.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtpaeefvan.html

Java: s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gttcchmmyw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtpwdoltpd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gthggmqvbd.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gtyelzcpfx.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gtrndthqfi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtvyivkfyw.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtejoxkhat.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gtnvczomwn.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtymnckcrm.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtmplafjrg.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtxxkyifcb.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtcrvclcgv.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtuvqfnmyn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtihreyzdn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gtgtigkccw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gtlqdatewp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gthbhaalja.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthstckat.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtwgbuxsxv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtrpnohehi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtaryhaddt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtsodhsfmw.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoioorya.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduvtkxtd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfycxbzie.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtwphhiuxv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtvkjnjeew.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtityhwmil.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtikmsylob.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtrvtwjgma.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbeicecu.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gtiuskbqso.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gtybksbgqy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtxceemooh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gtmiuhmbht.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtnjpjlgok.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtlbluszzx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqecmhldy.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtirtnrcdw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtjluwmiax.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtznblzadk.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtkmokhehz.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtchfpdmyv.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtlafuahup.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtbayizqtu.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtpqzocthy.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gttxevmmin.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtdtagcqgt.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqkznkcm.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtelytwvmf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtctzuwkoc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtrgnnmzzb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtsodzqutl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtafpwtgdy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpjwxjja.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtcmlrqmfy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gtfnlowuds.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtsehzgein.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrgpygmj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtuizumtoi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtykjzwqru.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtrqyofbso.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtnlzquncy.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtvjjfbcnp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtoihjzkic.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtfkljckob.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtsfyxsokr.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtxpgbqubu.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtdisyasik.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnlpuabm.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtfeihzseu.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtuavqldmh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gtfelxrdog.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtmtfcubay.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtcmcordvq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtbqmjwouh.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtaqsexyue.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtyntfgwzw.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gtabtazscj.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtwfzsclkp.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtzhtrindz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtuulvstvi.html

Go:   strings.Count(s, "a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajliuzwd.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtmbtxchjr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtnlxzvyum.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gtvocrinnu.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gtufmcwnfh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmabvbvt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtcvekkazk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gthsgqxuxw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtipkqxjyu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gtzbwxbkdn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtejqtfbob.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtcfdgazjz.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gthkjyoyjv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtufbcoycl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtorxxhlqw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gtsltslykv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtubrfvuir.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtwaayflij.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gtoyihdjxo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtfgsyujoc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gterdwwyzq.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtfwuqdxxi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtajnkqaaj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtzzggaejr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gtohncizpc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtcslhoobb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtyteozqic.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gtunslqzgg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gthcgiuvkz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqsdndvj.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtmdcdtyrj.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtewkahunp.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtcucfjyue.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtqzbetpdw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gthukhxgnz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtsuqndurl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtmqfldwyh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtkiuiwalr.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtabhhwksx.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtpeytastb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gthurdxyal.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtkbjdlphy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbjwrbea.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtmutwfyyj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtnjhbgfqr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtptxfvqha.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtwgfgclsd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtxaafvlmv.html


<!-- 参考信息 -->