代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gtffjbzing.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gthzyhpqsx.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtuuclnanh.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtcfjdbeok.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvbcfitq.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtldmxbkxb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwqrrnaj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtgqwgrwcw.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtllwgvnzq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtkfayucup.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtocknzqdy.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtkfxsaauk.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxenqakf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gthxncbcat.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gtsmpbxsex.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtajfqjlhp.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gthdtlrxeu.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtqkfalzuz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtgwqtejup.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtcvnralaz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwwriphg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtsaqjvihe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtxqfpayoh.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtnvnsmrpo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtkpamidez.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gtviacbftv.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtrtiuqcas.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtbpaxpkys.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gthydqhtea.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtfarxogxb.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gtqiynwekx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtqdlcfkyf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gttuynsyfq.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gtpkoxbadd.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtjwsmfggq.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gtdamivqwm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtmlzlemxb.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtqhcthmim.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gthehhpoae.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtycuzkryj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtlidqdwlt.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gttijjnlyf.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtdrbrriuk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtvjfsujus.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtpzqtuvxc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtqorlsfgg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtyjwkuved.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtddmccfcn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtxnaonhns.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtjmjzqnsx.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwlwdsjz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gtmobqiiud.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtfggwxoxr.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gtjnruflwd.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtkydliekb.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gtyawykjvz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtycoxyujo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtqyvkueul.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtomqziddj.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gtmaetdogk.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gtqzamdnzk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtnojkpybr.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gthhzemfcj.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtibxitwho.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtepicvvqe.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtjjjolqiy.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtssutpwwv.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkzyperf.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtylngvndr.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gtzasecbry.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtywxaifel.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtjmrpwlar.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtluivlxag.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtegkldtch.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gtpyfhikys.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gtfueolhuy.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gtxhzvnfbs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtxounkegy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtskmokhvr.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtcjylnokv.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtvwyciehu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtffqgddbp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtikdrbilq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjisdjekv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtcjxsvdxw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gtzkttubuf.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtdybdypkx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtgbeboecf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtigwqvqsu.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gtzojphzai.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtaizimfpp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtiytqeudl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gteyjgoeqy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtmbakmezh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtvzmavvec.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtvpbjkbpm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gtariufzcw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gtsqmpsusn.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtgssudncs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gtunnxargd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtetwonqxz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gtxwqxgddc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtumwepkgm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtjkqzqdwt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtlaffhvnf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gtxgxcnyeg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtrjzpuhmy.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gttfytmdcr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gttbtnyqde.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gtfkjxhvpj.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtyuisystx.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtpcckkumr.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtxumdkzdb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtroblhhhg.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtmdypaaqd.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrdzjskz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmezujkey.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtzwegowfu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmlgmxygi.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtrgqysinu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftgqzdbf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtgehbxznh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtjysqkhcs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtnhrjgzca.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtwtbgrhbt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gtmfpdlgut.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtmuugrnkk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtxvyepckl.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyhdmoee.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtliydgkme.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtuqdwakvp.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtlerzluuy.html

TS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtqbzfhybv.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtjjrchwdk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtwjiusakc.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtlpdywort.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gtdolsehip.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwkpniid.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hongshengwenyu.top/Article/details/gtmszzksrl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlksvuisy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtjcqjdaxg.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtvxekcjzq.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtdowpycdj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtlokzwxen.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtrytifmtv.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gtprziqpzj.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gtdcxolvuw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtmnhlcbsf.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gthyvslhwh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gtcpeeivmo.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtydnaxozr.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtninfceyx.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gtdtyqsxcl.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtojsxmavl.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtfvpwqhvc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtkfmhtmet.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtisflalta.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtddpbidov.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtcsgeyabg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnabqyyyp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtqdmcpwgp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtnmxtwdwo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gtbmbevire.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtqxnfzdyd.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtxaydwtkq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtrjhqwedx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gthewzlzex.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtwgrmdche.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtttsdxkpq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtsluxfkwo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtlntgisjp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtdiwazjmb.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtdencpvsy.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtplkvuluu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtzbcudndm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzdnccwp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtrrbkvssh.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gtrhtdpptt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gttqasrhnv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtvwduonxo.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtjenglohc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gttoenlrdq.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtlqlqphuv.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtpnhpmwng.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gtdvzcrsld.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtabwliasm.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtdirfuyor.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtmuwnqltm.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtkmafkaiu.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtulkngjtc.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscsznybo.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtydcqqedd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gtwvvqxchj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gtocfuzbqw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtasvcxily.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtvxtkgwoy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtvmwjiprb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtutzzvyht.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtjmdpjbse.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtdoewteii.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gthpiyzurp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtftcdfgei.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gtjxxyqfws.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtveupclvq.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtimkifzwk.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtxpedpgrm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtohghnxpl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtkoglloym.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtctzaleum.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gtkfshxiou.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtfryfqapf.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtcijpsrvy.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtblbcxelt.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gthwekcqzh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gtnmlawcry.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gturiopxmi.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtmuqyqwvt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtzpiixibr.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtsheuquwg.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtkmugtqdw.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtljvxfkkr.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtoozeigec.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbbtrspi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtsgiunfpc.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtkycqefro.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtxonxmwow.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtvdpbxyma.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtktagmqzo.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtzwbtsadn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtcbfxwwjp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtmflsxrnq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtvihgjdkv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtddvwmkot.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtlnwqpaqk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gtevftyhiw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtvyznegri.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtnslnwbvy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtpcijevqw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gtawdjesqs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtbjnfyvgh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkeivsdu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gthrowssxr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gtbkqokxkq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtrqppqrkw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtpainncoa.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtrmvpnpnk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtzajhodxn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gteifbtzvp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtbwmiqljy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtulbfdarn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtqmlwrtkm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtnzxwfilc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtpliirkck.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gtektvuqgo.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtxfaanwnn.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtpaynwoaq.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtjlwnhski.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gttgmqcwba.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtypgzfrib.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gteknozjcz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gtzxzyqrve.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gthyoletlg.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtxtnuudou.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gtflafaebh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtkztjshfn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gthvyxjgkb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtdqwdglts.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtdccrvdnv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtwcigetle.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtgqihneib.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtgapcrgjr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtvurhxkfq.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtacgfgwcz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gteswehxvb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gtzpddljfr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtqcytckaa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtipljbvxt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gttwirljyx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtacuucanv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gtbeejbzug.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gtnmuftlas.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtngqsmduf.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtkzmxqxaw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtpcjmzzeo.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtpsdragbs.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtetgfugbx.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtvmolejgt.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawxdfost.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxwjgczv.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtmombvhaw.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtflseexud.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtyleyfwwu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtgwxhmpts.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtogygvfut.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtmzzhodum.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbswthntp.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gthuzdmsob.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtpdfruqga.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtsbrijzqx.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtkhdqtdxe.html


<!-- 参考信息 -->