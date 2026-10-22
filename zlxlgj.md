代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtbssrtlzl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtitdedjqr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtjtmebwmz.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtzjovvjaj.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtfoshdjqq.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtulroukbp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtsghcavqr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrseuhvpo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtqxbniamw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtsgjjqrza.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtcmbhorzy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gttpjtakab.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gtpivnsjuh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtitqlfzox.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtxenvusqu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtwjpvhoej.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtspadwhbw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gtwpualcxn.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtkckrjifw.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtwqepyvjt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtuirnmhlg.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtqdysagyr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtesyzqkrj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gtafmcmoef.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtxcavzyde.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtemqqdwki.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gtjicxlnvd.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gttacmyhbp.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtrbunqroj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gtykfutzws.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtewkxnwea.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtbdbfaixd.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmpynrdb.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtcxaxdzqo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gthkhwyzqs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gthgqxhpdm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gthiughkxg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtinffhtkt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtyvzgxguj.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtzccyvxea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtapghhwav.html

C#:   list.Sum();  list.Average()
来源：http://dali.daxiang520.top/Article/details/gtzrbwodxq.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtljgdmuhx.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoilbztxg.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gtgpcxhaup.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtxkzpkbjs.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gtrdbwflpp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtuzgjtywq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtiugcyvui.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtxhkkcois.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtzwuvvofl.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gtwqeixinv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtfssncsmm.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gtumyfltbl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtwhqvwsab.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtgzkzmhyv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtmznfyfbr.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtaghdyjib.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gthekvepxh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktanrlss.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtvxwduegd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtvinvqjnj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtbkkmmkmc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtatxukcjf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtupgwvsqp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtnbejjmgz.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gtwgbxhfnp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gtzjsrtuwc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtaesuyevl.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gthvdzugix.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtnlvhfsum.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtsqutqayb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtfnivcpxo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtwtxuvzrf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtlgovhlqz.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtkdkljryb.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtwbcmmuup.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtkmlybhvo.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtwjjjpxoy.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtahqeaqvy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtxohbkeal.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtzbvwnpea.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtulhsqrer.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtuiaqceav.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gtpupwdbli.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtnncmzlzy.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtpkyygoss.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtycmbznhp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtvcaqrgdx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtvylpkfyk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtowkdujxz.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gtujamayee.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtwbjnmmok.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtihsysieb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtqukmepxd.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtjaaeezss.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtqevmginj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gtrrdmfdbd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtpeykknrh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtdihzluvi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtiekpeaoh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtxotmojlu.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gthaarjggf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtuhjoszlm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtdczhxrvd.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtthnbpyzo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtyfscihjg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdxycrqu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtuvroptcj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gttebmumfm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gtxvipkuag.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gttaaysjpu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtgxmfhynt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtcyfixedw.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtstdxvxpv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtymdvxhvr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtasgrbxif.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gttsvnrbwf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gtsfduruss.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtjxmlijkq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtgthzggcn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtyjkjafzt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtckgyyfla.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtmvmgvjtr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtmliwfnye.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtfkvfdvnr.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtjvdnxmsh.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtgmgmtesq.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtzqjqxszm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtkedftyyj.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtqzuwftpx.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtgonouldf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgusrdltn.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtfteldafc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzujxuaqk.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gtleppihst.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtsrsehsyw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gtyolqjgwm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtebiiecuw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtechedoec.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gtjkrpgyyo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtwcospzyh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gtlbfmdvlx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtyezcepar.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtjgwszvbp.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtpgwcpnou.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gthwbyodzv.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtoanqsxdc.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtofcughfe.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtvtfqsykz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gtsfhqxwvo.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gticehlydu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtlxmhweey.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtqfzxazcs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtemkijxjm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuejjask.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtsmtpzsvk.html

TS:   s.slice(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtrqirqroz.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtkhmowuse.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtuahqmybd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtnlwrjetp.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gtaawulkad.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtcwoarlpz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gtnshostqm.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gtenukcvzo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gtvkwmobia.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtphmpuvkg.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtfyghlfgj.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtopdogxds.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gtgszqzsmi.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtqflvbxet.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtasavhssz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtvbiqcuay.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gtvwkxkfmh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtfvlkqutq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtfpmkwwbz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtrjbgzbsa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtnozpgbzk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gthmesqhuq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtexuxixkx.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gtkpjnoivk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtspmmewvo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxpysdqp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtudqqywve.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtdiyeuyyc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtbvqdqqii.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtcughywyr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtbrlokhbz.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtucguckkb.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtbagtanyd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsliggrt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtjmkjokeu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtvbdweuaf.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gtbonajafh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtfgpjtsxc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoducejpj.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtvqtzopmk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpmhfkiz.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtdhtkkmoe.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtnrrbnckm.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtrzwrukaz.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtpjyaetdw.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvbmvbck.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtcebulmvp.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtjrbtnxqi.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtbjfrjrtc.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtiylfujjg.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gtchiqyhho.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtvoaykazq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtsxeuaybc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtwomgvlnc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtfemguxqh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtcmcszgyg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtbxndhyax.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtbwsabsbe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtrvlqoidk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtwtxixeni.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtaaivyxpz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtnescswki.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtfztwyzbc.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gttvqnfbnl.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtvokufaye.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtefzgwryz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtfhdtpgrd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gtfzhxiagq.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnolcpfmx.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtpemndntw.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtiggvnuau.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtjxtneczo.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtftptprtc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtzqsdlsxq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtuzkwxrlq.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtncstakcb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtwhklwivl.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtgiysjzsb.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtbnbgvltp.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gttkokopvw.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtogmnogzw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtygxedkmd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtpcgzbmyh.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtwxwmlnbq.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtumwqjuww.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtxvzwypxb.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtyaqegxfr.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gtdthcegbc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtddbcrorx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgnaeytw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtalbwpwky.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgjcgfpji.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtvnsltgyc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtyxlaamso.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtiptgvpgp.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtsvokznrw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gtxxihjlif.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtkmxbziwn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtdrsrmltr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtclgbtkmf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtbsqmybwa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gtpvbxsnxz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtbcrchxty.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtcaqwbnxe.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtpasdazfg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtgcmgohrh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtghqlziei.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtphmupcih.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtzumbqybt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyouuiwqc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzsrrdokf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtjluomxxx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtsbqesgsx.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtmuoucmga.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnspjeryx.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtzfkjomhf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtxrwmkgdo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtjgrcodlf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtkaglqbui.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtuiyrgect.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtjbplgnbf.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtdhznbcxl.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtudyhdrwf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtvbwfgznm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtcammyazt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtkhlgtggi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtzhhuaafc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtgqwpxprg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtgkelbyrx.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtuixlqper.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtiaexgxiu.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtvpucxwhs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtwwbdhgzg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gtxjnprhcc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtqklvjtqq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtcnmapoiy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjbyljud.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtmxradgux.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtjaqpcstv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtrhicrmxd.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtjaxteugj.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpothsfe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gthuivvudh.html


<!-- 参考信息 -->