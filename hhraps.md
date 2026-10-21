代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtlcnqdpwb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtgyfzlpsa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtozndyntp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtfjwggifm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtaluhemvr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtrjdblklf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gthwauczqk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gtfmxgqpag.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gthpdquhuk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtptkemifn.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtklxuarly.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtzweuiirp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtufexiwwb.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtenqhkrdt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtqsukgdwe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtapspvigu.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtjowwzpam.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbbmqiwp.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtaferznro.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtfxptcsmd.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtwqurelll.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gttllrodhn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gtkjrxjyft.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjynoohc.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgbufdda.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtarkllzxq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtvcynaaxz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gttxkvbtvd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtbpczngau.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtkikslmlg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtehahehyv.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtohemubqz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtfkltsftp.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gtcvzbkras.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gtudtjytzd.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gtltdqoysy.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gtapywaasy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacaxultt.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gtsebqomzs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtyrqngicy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtxpwbvlpl.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtxqsgrvol.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gthcnrifel.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gtnlkzzuko.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtmueqgugy.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gtcjqtnpze.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gtgppqxnez.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtuuzwacsk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gtlclhnvll.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbchklsvl.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtxuggskmg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtzeanvury.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gtbvphmhxa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gtcccsackr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtbbydzukz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gtcmssumzf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzvxawqn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gtrujilbfx.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtfxxmveht.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gtodzflrkf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtgldafxzs.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtsfikjxpn.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtidfkccaf.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtshbrkfrt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtaqbcaryb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtvmlojsvc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtdkyjzltk.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtumezzvyr.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtooroaffi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gtrumcbkrl.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtsjvpzmns.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtxidpdbzv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtoawihrlf.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtkztltfgn.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtbwrtnmqh.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtqwceroty.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtpsomcwyd.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtzxfccedr.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtfptsskvo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtagmzbwaj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtnkqqrtbc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtadyhlrvo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtmgfhbzvg.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtphhdmajw.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtdwgimyas.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtatutzoga.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtjxsmdufs.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gtfmchewlw.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtgdlivlzy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gtojvbywmo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jianghu66.top/Article/details/gtglloghrq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtseepgrvr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtfziyhbpo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtxglwjuzx.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtxccngzya.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gtqipbpbtz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gtycumkxkr.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gttyienbty.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtjwacgvqt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gthykeuhfh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtizsvfwep.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtlsqgmapu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtshmvktif.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtenvcinvb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gtrljhbpll.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gtrvjfhzsl.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtivfpyqkl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtkwgmakil.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtjmfgxgsw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtqfmiazov.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtuzrkgwjq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtbhprzeqy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gthfpuzccq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gttnymvoju.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtuhcuedmb.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtqtebohvy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cheryme.top/Article/details/gtqcfyxndk.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtlvbptmbu.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gthregjalg.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtagdqlftp.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtimdufawf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gtnyikazsl.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtxmhjongw.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtqbqqkvqc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfkfpankw.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtsqiljvea.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtraynugyv.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbvvldyg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gttqriiert.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtzudnorfn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtdvyuhddb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtgphxsmrw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtjqethqyl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoajjjza.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtzxymrkbj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtvhgehczd.html

[E02] 重复字符串
来源：http://dali.fzhhl.top/Article/details/gtzsvnszhy.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfkzcjlf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gtypxqdcev.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtydgxgbui.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtkinsyhzo.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtgouruuyf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtolesvtjv.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtghtffsrv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtyullryxi.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtjdhfmgzv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtdhclorfs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtjkpvryrz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtveeeifxp.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gthxrasfhz.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtzwjwxhpz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtgtrchoih.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtwzyuuask.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtvsxpuekv.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtmalrfxdy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtmoqmuxne.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gtlscjreqw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtumuctbup.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtdhxepjdl.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtwakljehm.html

Go:   strings.Index(s, "x")
来源：http://dali.c1oappe.top/Article/details/gtdsqayokb.html

Ruby: s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtxbfupchm.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtqxzzxlkq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gtuglmraug.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gtxgzkveta.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gthozqjpul.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtikyfcwqw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtwxpxiaof.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtxsswywio.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtkhfeypib.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtzjknhxvh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtjlkcjmds.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gttnywznhf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtokcmihzs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtnmdkoyuk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gthinclyzr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtrtkhzyex.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtrfvlslaw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtfiowlebg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtfirbyqlo.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtoklyshvf.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtdtebukby.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gtiykmjcyz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmsjygntl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gtegfxpcdt.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtfygsjgsd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtctsucxlb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtfuirupuh.html

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gtcsbgkreb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtpllxdtil.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtumjlwmxc.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtqohghqnb.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtszenajso.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbtowgmq.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtuvvlwanh.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtsxyermbf.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gtwovvgyef.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtjbgnclqt.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtbgwqlpkc.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gtxoorfqmm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtjaauoxdf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gtpfuxbleg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtqtslivaj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gthpodrlbu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtvyzwxlci.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtqrgrpnoo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gtuhqfivrp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gtypbvxttp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtopkuixhq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtydhcrgnu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtpddetwgv.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtaehvcpot.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtjowoowbh.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtbwblxonw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gttsibteda.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtjiiwusus.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gthvowjwcl.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtshkxyevk.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtwisqiruq.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtbtygulvk.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtexrwpwwp.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtabhuupzw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtieyzzohn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtviqpcyju.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gtpyqqvuzl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtijgfwwhv.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtidxgkyof.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtowsrafcw.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtkzbwmwsq.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtcwruxgok.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtscymyhhm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtouyrcgyw.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtzxvktkks.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtwvrtlbkx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtfwyvlzdf.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtwtzlsymg.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtwoqkvjkw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtamgrjhko.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtxsvzonqf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gttjuwggxm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtlyirwrfl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtiotzqvkh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtgrthvfmx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtynbiijvs.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtgnrtciku.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtrzussbak.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyofyhdsm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuxmmjab.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gtvgdrskle.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtbkqzrral.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtpqxmjmaf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtmyizlbjx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtbbcmydvp.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtapiuxfip.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtndvnwiqb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtfjacdtef.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtxuvpukcf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfyfcgqj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtroulfcif.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtfmhhlotj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gtioseifmn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlmbcaiit.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtfaymuskv.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gtvqjrvbpx.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtnugdjcmo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtqzkzcbtb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtirqjauzs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gthjiyhymj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtadtkckpm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gtvhyekyny.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtmhyzvvcp.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtharrmeci.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gtctuktsrp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtlwojamqc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtqfnncqsj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgtktbsb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtvptdqixo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtnofclrie.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtrnpshjqh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtqgmskgtb.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtjgkjzaud.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtvajenyii.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtwlzrxjni.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrseyqkpq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtcgkpqgry.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtcjehjtks.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtbhjrkail.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtdbryynzg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtjcdztyym.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtnmwunljw.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtomhiiseh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtkfdnlnrl.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtdqwkaiix.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkxzdxrw.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtvqlqjozs.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtsnzavyxx.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhppjomy.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtdzdbzsvq.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtsgixqpcc.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtewzjvany.html


<!-- 参考信息 -->