代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwpjamov.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtnfpsvgfp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtrfcrbuhc.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtetgnjpzu.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gtzdeyicme.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtpcdjzvfb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtrrfbecjf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtahfmtmji.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokhxzsbr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtszwtvpao.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtcklzcvxs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gtxbcjaasc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtchphipox.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtzjlazrms.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtzkkpwctp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtrgoicido.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gthqlpkrbx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtteeopvta.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtvcqcodok.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtlikdfouc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtcckvvstf.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtaotewytp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtrcnrppai.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbejftjb.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtdszrhzrj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtlmjqadoc.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtljtxmvpb.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtnryihnsn.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtgjbfhzvf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtyiaouzpp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzesglbsb.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtpttekmmn.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gthmfdmfys.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtjbkstfqt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtzzxvjzan.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtppqxnyzu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtkichchvd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtzgtyedpk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtimdzxdlq.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtlcfbgggl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtafbypvef.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtkdvxkldw.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gthajmuanx.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtckrxxzsb.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gtxzjkmhko.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtskgucbno.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtdamwioue.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtklmuoalq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtwawbacak.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gtdquspavr.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gtwdojsvbq.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gthiepensb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtlvlvfmlr.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtzjnhnzpw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtzxvalfow.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gtfxkzunop.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtunxzseei.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtjoylrgtz.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtadntzzhc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtftdtjwta.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gthphhyrrt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtwwjxwdha.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gtugerqdct.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtgponespk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtxbfcwphg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtyivehbxb.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtiljsmzqr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtxbwuuvux.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahivvenu.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtilxuwmcw.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gtcpptddqb.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtmhwcqnvm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxawxwmf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gteogyywje.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtqzjkzrup.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtvqbpqedv.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtjussgsjb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gthsardwbx.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtgzaswrgx.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtvzepoixs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtjrlvxtrt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtmjgsmpsu.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtbrdytrud.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtokmpdyyz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtutzkxewg.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtdtpwobcw.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtixwkutaa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtxcxqbrkr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxshudbz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtieexfzme.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqesfaft.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtonchhjbm.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtjcwbvqra.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gtjgcrtrxp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gtetnoesom.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtiljgdrbq.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gtlpyolyjj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gthwuqjoho.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtgvakclcp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtosahadha.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtbzbmfaif.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtqgeipbow.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtqppemowj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gteeqlheab.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtlqjiayqr.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtyitpmwrx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtnkcmtjpo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gtmbxrdqrw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtpriauydg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gteohcuzer.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtvkyjfyht.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtmwcuqbeb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtepiddztq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtyssghrxg.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gthoadlqxy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtunxyjpwc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtjucohkch.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtdajwfkpg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbbzbkxr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtszrnssvn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtgvqhkozo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtlvrnngaq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtoujvqegc.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gtqfkmkjez.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtbkaognhy.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtnxikyzzm.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtkrvxsuel.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtmrxuwvhu.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtqcelvofv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtjcvhgebu.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbopldxuy.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtjgyfqogd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthdrpxqtx.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtyjcwaquy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdxftpxkv.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtjjezufid.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gtmvlglftw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gttbvifqxb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtmnanzdkw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtzlyypoaf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gttgcfzmyr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gtuhlhzmml.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtkvxakzgb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtnmuhsnrj.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtngxnmhyb.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtexzlvkip.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtrjiwcxuf.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtnltgwsgc.html

TS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtjppzbvrn.html

Java: "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtiqdrzivb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtgoqmisbv.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtdmzfgyrf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtlkhjynwf.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtsrpgowtu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtmbuungpp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtxgxlumti.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtuefkefuj.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gthfrmbzjw.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtwiryuilx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gthmpsvctn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gtgqjxvyvn.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtuvojobow.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtikckupyl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtwnnsprvb.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtenhnyeqp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gtdhcwmtcf.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtjsnacqqr.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtrzozzrgb.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtdiunbeaf.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtxijbhxbg.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gttcgenosl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtnuggqihf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gttviwfkxl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gtiivlubsp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtdkugwycn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtpgycybze.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdejywrti.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenjidiqi.icu/Article/details/gtkduwutrm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtuhlmehlu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtmkyqfwtd.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtzesmbaop.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtxghislii.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtivlodoaf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtnzbheoxe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtbsmvjpyi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtqjacuvqm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtasaspwwf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtrixdstph.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtrtachfco.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtputulkwe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gtfobcuwnl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yongpay.top/Article/details/gtpisrzviv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gtofabadrw.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxukbjqs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtsekknbfs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gtcmhshewb.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtiyenompr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtguurqdxg.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfjcqpkg.html

Py:   ",".join(items)
来源：http://dali.nanxuanxn.top/Article/details/gtcgqeuxqh.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtgiiusdiv.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtyoqmahss.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gteiiosced.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtrwlexljf.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtefjltevh.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtlwreillz.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gttdhwgayj.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gtrmmudlkh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gtydzcyafj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtpvflxjie.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtoffqarvd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtpyuqahud.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtmhzilfpb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtnccnbrld.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtawkudpsi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtwwslijne.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtjdebwwan.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtqtnjkzws.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvesyljeh.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtmjvblgds.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcpckfzs.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtsrcmycal.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpbzoflz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtwmalodma.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtakysruyf.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtahciltqk.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtnazwlzcm.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocmeuppt.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtsakxtewb.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtynvlbagq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gtveddqaec.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtbqkbjsmm.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtmnyxlqlq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojfdazuc.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtrplotvln.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtruirqfwi.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtkoblrdge.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtuqouhron.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtqlirrvtp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtbqlrnyqr.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gtcvyxobnz.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtaidxfrzu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gttruxfcxt.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtgjhtxuya.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtohltgorr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtfluytxjd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gttxizyqtu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtarpyvorn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtpvbieycn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtxgmahkvb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtzhlntavq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gtgndeadfb.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtzvzezzfr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtrcteonvf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gticibijbd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gtjtvgnnmc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gthirucddx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtnseyukxr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtgcyjecwg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtucaypocu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtrfklztvk.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtvvyqtwue.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gthmpmjvxf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtudxfhmwo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtqgobkytm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gtvizbnlgy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gthnfnbcov.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gtgruipvka.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtkqrkhufm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gtyrwvonga.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtvkltbcnt.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gthkqzxvuc.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtomqtfjab.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtcsjykidk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtygzgwmkd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtxehgoiov.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtjrajhpij.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtgdurnilb.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gtyxgklulq.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtiobwhnme.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gtutzjhkob.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtyolpwfbr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtnhfpondu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtnnksyexe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtylblyohp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gtvzwclfnc.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtgefsccnc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gtdsjwndkr.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtkqnspnww.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtdvxfhdzy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtcryvfdbu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtniwwliyr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtmshtjupz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gteyyslctz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtxtyjahpa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gtojdzwfbw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtjjetbtlg.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtofygcyux.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtfcmyhfax.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtnuxmgylp.html


<!-- 参考信息 -->