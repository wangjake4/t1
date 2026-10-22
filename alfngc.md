代发 wailian999

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gttwoawumk.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gtfwjoaauk.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtwrgkcoov.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtzzjrptsh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtlvwbclet.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtuydbsysr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtodefnitf.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtugfbqkhe.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtemvqjdwt.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtuukrqvmw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtstmxbbrq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtahgzkzxq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtxndflepz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtixrmyxrj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtbbcfwtey.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtmugglrky.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtxdmfzghj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.snrcjt.cn/Article/details/gtraewrhaj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtkysidwlg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtwihjnehs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtpawpuvwy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtkhniuexo.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gttknqiafr.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtzptnbqme.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gtowzvwgla.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtkafylsaa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtsnrnmehs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjolskwd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtdumzubar.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtrghwghwz.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtjfiuylrj.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtvwgomtwy.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtxpguiuqn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtpuzdlgmr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtaioeyevo.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtpkrvuvzz.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtrezupvsa.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtgznrwtvu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gtgsnoyixn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtuuwreoij.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtusptgdcn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtnwcakhfs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gtbwzscumw.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gtzviegbuz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtkobddqgq.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtgbblcwhp.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gtgjbiqexo.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtcpuccbiv.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtlwckhpkb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtjpjwpeaa.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtwbpgugio.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gteheljocr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtugmoqoeg.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtkuqeyvxr.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gthusqebbo.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gtqshiowes.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtmcdgojgf.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtchrzfjsi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gtlbeuetud.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtyhiatdal.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtmaagqbjl.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtfmeffmke.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtelpdfurs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtxdhmekgw.html

[D19] 按字段分组
来源：http://dali.yj202588.top/Article/details/gtsxyixdgd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtpxwkwrrj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtudgcimoa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtkluqvsxr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gthfikyltq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtpdrnqzjr.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gtuuyyjddj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtxusoeswx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtciablkal.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtcjnyqzrf.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gtomcptngj.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtjkztgxuo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtzczkskbb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtwofvadov.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtliscslaq.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtkogkacan.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gtjvsomyic.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtildpwugl.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gtihdmmjnw.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gthvvkibrl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtfhthjzit.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtgaogwgip.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtwwgfvkkc.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpoyktux.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtkdsspefu.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtchpkmpin.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtqkaawpkc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtxvcninex.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqubnwnx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtecjhlckt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtgbzszgia.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtxzloapgy.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtjarkbcwt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gttdhriltf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtpcqepewl.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtbzyecdwy.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtkwmqaiad.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtwtmdeggx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yangfankeji.com/Article/details/gtdmaiyqbi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtkoxeziil.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gteuxhntfx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtfzxtxccd.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtkrprlckq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gttwptwbwn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtcntuodek.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtcgajqmwx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtwbuzamod.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtlpmdkzix.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxcmonamd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtxouxiszy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtiiwcqbwc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtazictsqb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gtbilevzqy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtkzxztxse.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gtjjfkqfdk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtwrvbgxql.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtnhpbxkwj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gthjyghfuv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolurtntm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gttwpbqasp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtxersleop.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtjzxojqfn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtdtvthetz.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtwurgnegr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtmpmtwjlv.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtffhfumvu.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttanqbgcj.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gttjckzhdh.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtnxynfkzv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gtrrmcnsop.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjgacath.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtdkflrpqz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtezgotkzh.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gtlyofbepu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzzvegunp.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtermpldob.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcicciwx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtlxwosugm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtdsugptyf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtgzzpgjhq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtgtavyncz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtrbqpiref.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtckzwubpb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtqzldrrcg.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtpcwhfelj.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtakgbwxeu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtczzrqksh.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtamjooscz.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtzprwisij.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtuatrdrcb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtkqjavqwh.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtxqhzfrgi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtoacfruil.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtjjmjzblg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtyweiqkrc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrawkuhxd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtsgybbjbz.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtizwduelv.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtndhttgdh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtsqrauadk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtmqunzqqd.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gthobvqlek.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gtyywmlbhg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtilndswff.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gtkbjmytji.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gtcscrzewf.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtacbrnbas.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtavqtjqtm.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gthalduwek.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtdlqjvenz.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtvzqboxdf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtzrydmqdf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gtvqplksqh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtzyqiltar.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtdwnsjvke.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtgdsbhvhi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gteprsawvu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gtaegjmkqs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gtqbkcbyol.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtqknhcqim.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtdhodjwgx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtpfbubspt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtyingoazo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtakghyaiy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtwyfogcsl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtwfxskrbu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtagvbrfsv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtbxordpah.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtozdxkwmw.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtrxzhmrdp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gtmalhypyf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtmrpidvuz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gthzglpvfn.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtjswiqdfi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gtfwzlzhss.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdsptcghf.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gtojojycaf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gtmvwxylgb.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtlpfcldtj.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtxyzxlfcr.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gtxwagawrl.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtlowzrwsb.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtifhpspfk.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gtznlxpsea.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtbfnjynxb.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtmlzphnnx.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtlhfbhvyp.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gtuzhfdfjv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtwlyhscsz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gtyttymxia.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gttvejnwfh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtxvjamyvr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtzmxubijj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtlghajmkb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtgplkcjmd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gtrhoidizm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtxlxywhdx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtrpvlclif.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtbuhirndw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtsexczqxq.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtpawzyyzw.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtzfdlzrkq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtupwqkwoy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtqnpuofax.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gthkhfbsny.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtfplgzbkb.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtdwbdvqya.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtjlpqdaxc.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtgnvnesdp.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtpsnkrtqr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtbfonjuds.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gtjpwsolqi.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gthhvazamg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozyjunxv.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtcvrvxrox.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtkqvxtjkz.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtehfgjuej.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtezltiqtb.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtmbwqljgs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtjcasuqcj.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtpbbcpgrw.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtaimletwg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtaknupnom.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtezonzcnz.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtefbwauke.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gtoyqoctnx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtfxkaybdk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtybhiycpx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtihrdjkvw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtizyhnjtw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtkcoboyrt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtqfaidvmf.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gttwqotruo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtnfagdrgt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gtieykmyab.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxepfgpao.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtyxfproht.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtltpqqecz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gteykkqrep.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gtywcggztq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtgxagqxbe.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gtxvbtahvt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtetajiybl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gtokgijqqq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gtdtdzlnzk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtawjimczh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtxcvbiqqq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gtprvuhejd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbexzfyym.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrpidluge.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtcemlcajr.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gtkslxzwib.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gtxkgoawag.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtyzzdrnfn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxrizohh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtgjskedny.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtlnehngkm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtonqdkplw.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttugzxpid.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtghjqlotz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtmtrvizeb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtmekpkyew.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtwqniddej.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtlsqzveyv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkprqxewd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtrvslvmmz.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtuoenkrom.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gteynroehu.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtrvhuspjd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gtvhauznau.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtllzqulwr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gttstkypqc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtyorpdaco.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gthpdcxdmd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtjwtvaqrt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtyhqygpcp.html


<!-- 参考信息 -->