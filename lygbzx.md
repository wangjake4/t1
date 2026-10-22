代发 wailian999

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtrfftnmsu.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtaokwxljp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtdrrhxygd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtjgqsnwua.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gttefjbzwu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtnkocxivu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtvkkdgwap.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtimdfeehd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtxcnngosb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuanzx.com/Article/details/gtxohofvmr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtvuneaeie.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtgqevsmww.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gtlfsjojyj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnhmtvty.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtosuluuuy.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtsbrtdsjc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthovtoduh.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gteazzreqa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtykghkwys.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtaaefirrm.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtfrdbhgut.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtlcmmbcra.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gttbkpinch.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtjddlmrgz.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gteybopbsi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtyjoznnfa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtasxgyxqe.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtepgdrghu.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtjwayphlg.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtdaenjytj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gthgthxmlw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtlihalmrj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtkljirtqk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtmwevmiau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gtlwklwgqh.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gthoitoesd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtnnlcmwii.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtbqiinhak.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtbvvwtycc.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtimicrquf.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtodtncwlk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtalzbssmn.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtanbiilts.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtenrbqomu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtkbxuplol.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtalvttbjm.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtwymlcwkx.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtcdvvigrt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtswiwwgmq.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtvzwndgjq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gtltwjfdta.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtwfanapzg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gtosthplbp.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcymbfzjy.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtdysvuhgm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gttpiftyio.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtigaivjpm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtylovaltr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvzywlau.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gteycoocmv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtxyzixqoy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gtmqcqqyaw.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtqamqxnou.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtmoiqlziz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtuwhqyxql.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtymjyfbrk.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbkyqugg.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtocwdfxyf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtxznohkom.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtvwjshyps.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtkhnrsgdg.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gtpzxdculh.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gtebelgpjy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtmrtmxvet.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtjybrefqh.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtwmyossyg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwfkjtct.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtlpopsauw.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtjdnxldkt.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtilzzwtht.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtqsavxshq.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbojacqvq.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtmegqtdrr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtqpcvcbwj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzvstyqq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gtysefognc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtbhwqqxkg.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtetqcgfmd.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtkifvlecu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gttloxmceg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtfstzoija.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gtzfwfxbgk.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gtxzfwzgog.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtywyllwgv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gthjtkphmj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtmnnivlbt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtuylriaiz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtivvzmewu.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtvcgdlsrg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtcmcbprej.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtekpdldad.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtwatpyooh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtxzmnanqb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gtydldgxww.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtlvuqgsgn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtvkcdzkrk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtcmfraybf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtejjwibms.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gttlksbtfa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtttamuihp.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtamsmrgab.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtdufozyhs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtdptheldd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gteiftfdha.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtswzugrpq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtlgljvmvt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtbvgdtabi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtvodwnxxg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtyqkndvdv.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtyriixrqz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gtnazwthsu.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtzzqrbrdi.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtyljsdndv.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtfozibing.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbzsvrvg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gtswkasrae.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtkfsrsioo.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtkqmizvxo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfgxmlgar.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtsteoxbgr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkbwmnoma.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtybvjnbhp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gtheuhzluc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gteruzjdil.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gttgkdpjdy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtywbrlxbt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtsrgglevt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gtfnpvmjrr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gtgqhfepiq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gtjsnpmgsz.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtiqkutxok.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtxdiotiui.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gtebinrlhd.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtsoobnuok.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtttriymed.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtvafzdxuj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gthnsiigsh.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtcrehoplh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gthjbcseoc.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtukukhlll.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhaasizr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtnggjownh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtpyixjfwa.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtnlrtakfs.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtimikpgty.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtyxnhhluv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gtgviabqxe.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtvoxmntsc.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtmdyogucr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprvhacpu.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gtnhogxnrv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gtlnauhppo.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtfmsxqygi.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtxdbrctzf.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyuopyen.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtljuxskkx.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gttoohkadj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtzdrnysde.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gttbpwncrt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gtdllbqgxj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtteeqggpk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtwudpiujd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtnqffrmyy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtgpexgcro.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtbsagzkhu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtdgjmyaab.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gttzwamthw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtzwgebwcz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gtmeuawrif.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtfkletxeh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtevovkjla.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtlmnhghvq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtnlsjzcjv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtbgewduyg.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtuqjstucx.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gtgamvizrk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtqqmrhalp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtjtjvecml.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtqizlghpg.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtfhlqgrrz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gtauprflur.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtbmjsedga.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtvtbkrtmc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gttgeyuhcw.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtvxpjdimf.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtojygdpna.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtqgcjmlwo.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtntkimgmm.html

TS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtdcvwwgpu.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtdxeutiad.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gtsoomxqpb.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtapxbinek.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtmvupvgti.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtlqlhykmj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gtazhdsgef.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtfrocwfyl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gthtqpwgrg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtpugtocvi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtwhchgkou.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gtrptrzmrk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtaccpjjfc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtikteyqac.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gttbucghkk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtnstyaqku.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtktvztlgh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtgleujhzp.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtpbbkqulb.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtbhvttlgi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gttxirrrpo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtrzkunhif.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtqzumnhpv.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtnueeezqz.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtahgvvteb.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtzxnowerr.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtcinhlllz.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtgsigeqdi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtihltopqd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtgihjxgrb.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtdakukwed.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gteldaggzr.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtvxaetpoi.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtxgsapgzy.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gticpjhzvq.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtosnplqdx.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtkhrgmzwd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtkahnktcr.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtelgpyqbp.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtlqrokatz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtrehpnjuw.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gttryhflxt.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtwedbpyng.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gtsvnxubqu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutkembmc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtwahhqjpx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtlgqzefak.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtrxkmyjgv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gttyfwqthu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gtfpxsnhzz.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtwrtuaght.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gtgonyoiif.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtzlztedkk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtqjjsuyfq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtzcayenrm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtzucpdrer.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtwybaoqkl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtgkflfpal.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtjgiurlde.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuwzwekp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtjgumusme.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtmkbdsekh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtqedzdxlp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtqlxknioi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtsxaxnrim.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtwacfgyad.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtgvynjoej.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtgzzblgpu.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtxxztdkpm.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtcrxfwfjo.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtbnkttwau.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtkkdyznkh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtbzgdfoaz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtjxcfdvaj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtgulqjgys.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zdqjudy.top/Article/details/gtwuqpzxbc.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gtbrvutcsh.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtrqohjpof.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtzggfvyth.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtbcfzbnis.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtoaxyumee.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuybwuwbj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtiopugzdt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtjhsgcgin.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtigwsrrjh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtjqpfowcw.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtcvxxbcpz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtqyfatjcy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gttddnfbex.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtlcgdehuq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtentzuprm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtcoswiqsy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtyunfztfk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtowjwkmki.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gthqcfjvpq.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoxxjmou.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gtabtehevr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtcivinowq.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtzlcxftli.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtalvirsfp.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtumfbnxkf.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gtdzfmmjvi.html


<!-- 参考信息 -->