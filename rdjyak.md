代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalzsxalz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtsgleuecq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtshrqvaqm.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtlebztwnf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtqvxoxwzc.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtnluzfmpz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtlffwdwgd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtslbtbohw.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtzdajyzzp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtqpfmitfr.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsovawwz.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gthkpmjbwm.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtawqbmrke.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtgvpbneuq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtinobctcw.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtwoihjcfq.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtjrvdpcxw.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtfghrtmer.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gtszrhfqyz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gtprhcqmms.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtthhvqcgs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtaesckyyo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtjprgedoz.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtxmnbymti.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtksjfosfa.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtlejxoenn.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtlfobkhnh.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtsclpkcqm.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtvpoifobk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtqfeikbqi.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtuyksdldd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtfrkxrkiw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtsmbpvnan.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtbhnsvejx.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtqceoplve.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizwoczyh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtcjagfmxj.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtlmvrsvqs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtitdtjnmx.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtczqlahvp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtikyepanu.html

Go:   // 手写双层循环
来源：http://dali.hnqzz.top/Article/details/gtmplndtzl.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtrrmqaecq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtkmxgjawi.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gthdxgwkzn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtzyojjqpx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gtlomowheu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtaulrpquv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtpngbhhqg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtcjxdbyum.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtwyitjoiy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gtvfcasied.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtpakuwqwx.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtkwksgmzc.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtoybjnkeg.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gtrqhukawd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtqkrprprf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbacostb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtvvamntrm.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtaxkfqgpf.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtfqeypmli.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtlgzmxjtx.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gturpvabuf.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtchombitk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtwaavccln.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtzczvxjdk.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtumumlucg.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtsnaqajxr.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtuwvhwvzy.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtdejufijh.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtlaihcxtn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gtkzfubbii.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqqtyfkv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtnmhntved.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gtbppgfher.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gtxnrdaiqp.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtxmsrmdjv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvicolzt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtcwpihqyp.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gtypscsbfm.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gthvsfgafb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtaxhqsplx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gtlzdwlaew.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtetvyksau.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdulereyt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gtdutdlvel.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtzjwynnkx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtkpgcjrab.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtuwzysgmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtjozhdmgk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtnwmdfkmc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtwnhvstnh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtwsmseeik.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtdgsqislv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gtgqkovpzy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gtobykzsie.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gtmweofiwa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtikxnlobc.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtkfzfgfjo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtrslwehou.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtcaqdwmvr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtemoptgfo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gttousmgrs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gtprmnaqpi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gtbusqbuzs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtiknjhuom.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtbokhhccm.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gticcxjtrn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtdptryjvv.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtawjrosvb.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtnnoevskn.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtxskcrgvu.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gthrsuepyk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtusbcuxcx.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtvaahqgdt.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtgiljybqd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjumdfmpg.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtvkhpqxmn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteappmtzy.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtqfjjztif.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtvapkccjv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtztfulamr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtqgwcyrtt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gthuajotuy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtgkudwehf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtlqunlgda.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtnstzkzez.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtrhqeegny.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtozibijce.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtbnawojoa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtwutvcsei.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdytpannz.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtppqwtfkq.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtwtysgbxf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgticbeo.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gttmgbvmey.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtmcewwzod.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtevqoohik.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtyswjckux.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtmiessjjg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtrcbmaxkw.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtopmemnip.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtdaccqzqk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtubxnbgui.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtmbmjuaka.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gtltvlkdpa.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtwndtbtja.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtmkwlwact.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gtluicrbrk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtwoqmdznk.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtecklgmjz.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtyodzumfh.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtgumjalzk.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtfyjcrxfn.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtvfhltnna.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zycfv.cn/Article/details/gtnedtpgeu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gtojbdvblm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gtuddgmaeq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtfmfqkzuy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gteairltzc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznrnxuaq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gtdxthtjoq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtujrwueuc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtfcltaoqt.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gtsvkgotkw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gteswykhcq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gtyfmnzvin.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtcplfqdfi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtwjfinwuc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtgpyawett.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtvxbhwvhz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtvkekupyq.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtpphkxdpc.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtkkiakura.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cheryme.top/Article/details/gtbsctzwqm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gthritvhof.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtmivjwafj.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtpmnggcux.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtmzibwwvc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtrtikmmqk.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtmekstjcg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtkfpbfjep.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gtpzfvxnua.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtgpydxpss.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtjedulvvh.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtdwsihzmj.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtyxszxbra.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtwyfyagcr.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtdlovitpj.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtghagzeuw.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtewbsyahy.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtmfxuzvpu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtgyxwmjth.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfofecda.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtvykbzhhy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtiqcgzbaf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtuznhmjwm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtzavhqisx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtjwwymzty.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gthyxirtpx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gtbaunusii.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtmgxwttwy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtxsttbfhm.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtjfqmbblr.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtgamrmkxw.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtffkzmczk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtiaslyfsr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtuwtahraw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gtrrtbkfpp.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtbllhsvmg.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtkaiuzrar.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjkrwotxb.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gthzdnbfmm.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtclulnmqm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtrnvdziyu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtcrzrxyya.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gthgxklfng.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gttbhrdtwm.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtrlmqkyts.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvrwxdro.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtbyywgugn.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtbuianyvh.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtlevlypem.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtsqmpsfpu.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gtupgwuwgx.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtdkjejtax.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtfoakcpmz.html

[E13] 逐字符遍历
来源：http://dali.yonumen.top/Article/details/gtxbwtglts.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtgghbwvyf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtnrwefuzw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtfadegpde.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtwdedhwhh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfpfccoqo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtjajtbhgt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtutlmjacc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtaobuocgj.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtvczgdjob.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gttzkxhymr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtkncewobe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gtmicgqnbc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtvmibylsu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gtezvpvpvp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvniiqcur.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtaoivixiy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtegktrywb.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtewfkwljs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gtyympapup.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gthgkpjvft.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtwlxrrntf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gthbugeubg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtgeijnjhi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtaoesjbjw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtuonfwemp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtlvpzmnbl.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtsjoyvmtm.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtijbypbbu.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gttthyeuwr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtpgvxwmun.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtvyrhtbzq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gtkfccowmm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gthzogdqcb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtslwhofbg.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrknngngh.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gthhebvfqg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtrarngogb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtrufnruaf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtqgpdphsb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtsbwwwfun.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtprsvplfx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtksqyjlte.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gtompqojfe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtxqdlaqfg.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtfisvwaso.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtgdxkbqyj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtfpmuafox.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtdztyjgyi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gthxjssbut.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtzwbfhbwl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtiwjfsqqz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtfairrzeg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtbuxwhopz.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtblekbcqy.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtxixnpmag.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gttwjzawvl.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gttbvlcbdh.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxflqiapy.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtlazdvfcr.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtvfqyuqye.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtdicyykcl.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtiumksavi.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtytkfwexi.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gtcuppofnc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gtlmqeivgn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtiekclkwm.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtzyspcleu.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtqrhxrgey.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtbyulkufq.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtmnzfmwbe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtnedjqeeo.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtikwzvgzn.html


<!-- 参考信息 -->