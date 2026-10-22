代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gt2ubevfxwb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2vyihthwk.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2ovujggmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsknwiva.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2lgtkvxjc.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2xcheyyjm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2eszoglog.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2nufkigeb.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2ogbzenbi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyrfuyll.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gt2vigtufto.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2pmnikpnc.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2hurihphu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdspklun.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gt2ctutflyk.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gt2fpxmyjyk.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gt2zggbhctb.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gt2pqjbqznv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2beqcppbo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2miyzmovf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gt2dbbpdnao.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2ofbwklpa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gt2krrbtknm.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gt2rgbzeiik.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2uvkevfxv.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhvjycgm.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gt2kmebrzml.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlcemocx.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2hflgayzv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gt2kjgsxlwv.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gt2dfqhmmto.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gt2rppyfefr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2rbpvmfiy.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gt2ebhqztxy.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gt2meaytywy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmbattjt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gt2qeqthgwr.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxnnvedj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gt2xprechqv.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gt2bxqyezdo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2ynybcywd.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gt2ahmnntqq.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gt2frlluvcw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2mgulyusb.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gt2cazmrrnp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2uucqglyi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2chhfnepx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gt2nibxbjgy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gt2ulylrhgn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gt2lbahfemp.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gt2brqqpabe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gt2nagevggl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gt2qcogplya.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxzrtrbe.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gt2fsfvzvpt.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2madrhtzb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2rxnuytci.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gt2xbepojxe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qopuqdpi.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gt2rvonzpgr.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gt2apmviplj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxwruwba.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdrjhiwa.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2fcwdccyg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2miweuycl.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2vzzmkfum.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2nqenhzbu.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2wkwvtxke.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ijefbxoh.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2siodzryi.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhsjabes.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhoelhcu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2vunqodgj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffirmlyj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2dkxjjpbi.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gt2vjzmhpuo.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2ehixmchs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2rpidpiac.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2lenbdwqy.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2yznaztdu.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gt2djzgccbf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2nneoraea.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2imlwqabp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2evyuhegr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2bcueyvcz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gt2pmrtnqhs.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gt2jxbqowwl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gt2eahxkfkj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gt2wzsrujbm.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gt2zsfxkcyi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gt2grmthqsa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gt2qaadbbst.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gt2kfnqgxfo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2ohluakjv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gt2oorkztgx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gt2ncbqyqri.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gt2xkhtuejm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2zzvnixjh.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gt2bjrrvjds.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gt2plramlfk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gt2ujbqtaqi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gt2pxgcnfsr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2wxxforsf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2xfkdbfsv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqpnuvln.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gt2rldzqqlk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2qmcbegww.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2vvmuiicq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gt2brgdeuhn.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2zcchcbri.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2mfzxfaif.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2gzqjwish.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gt2bgiwaxdb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gt2zpgwypch.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2utxxxxcm.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yujkdtat.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayucujjr.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gt2fsenkgbm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uxpyizdg.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2kebunrzp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gt2fbyaegtc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2zrszjjxc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2bfekahon.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gt2tpglzxsz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gt2cjvwebfr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjndktzb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gt2nfufndqj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2thcumgbb.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2czdmnwro.html

Py:   "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gt2zryaffkm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2augvcemg.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kixbhsch.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2pozvabha.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2revkjbzf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gt2yvpaquxy.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2wizkmuur.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxvnbkxd.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2lkrzglgm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gt2tyixmvut.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2ovmrfwao.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2cjraapcs.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2bwfznbeo.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2wxurpeoe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2swrsmnjc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2szqmgzmm.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gt2bmyliksz.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gt2ppeiumpc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2wdienrhw.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gt2ltbfbief.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gt2zaatcait.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2qgahrtxd.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2nvgkbwhe.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2ckdlbwis.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rakykobb.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2jucnrlvh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gt2jfegkkie.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2ciysrhmm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gt2ohxsplaa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2fayiwvjd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gt2pcnrwigg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2prgcgurq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gt2ttsqvxpq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqkgllyl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2stggkqgi.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2zepkdnnc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gt2buhgeqha.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gt2glricqos.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2nzbkotym.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2pdsmwziy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2nrknrqmc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wywxwoam.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2nrqfelai.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2mwiajyhf.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2ahytexds.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gt2naqmeaql.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2awwmoyue.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2csboooqa.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gt2psjnbqyq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gt2gupadywo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gt2vqokbths.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gt2dovbxgda.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2ssblpibs.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gt2xmgszgot.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gt2unaecxes.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gt2wruosbun.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2sneegbgb.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2aiybktxo.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2cslydzma.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gt2qqttfejf.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2gecxyqax.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2vciuscjw.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gt2qqkyakxk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2jhkbacrm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2glosjsgl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gt2ynqmabqc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2kjelelum.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gt2jonqbibk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2ssvnibii.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gt2xagstrnl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2zysdbmlk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gt2hnnqiksz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2vjvrnrfu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gt2mljpwpms.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywsuoxjo.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxkmxvhp.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2ndgcxbtc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2lmvaocgh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yucaiknt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gt2tdjtgvfv.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gt2hfpzzlvj.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flzcbsnx.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2gzharnob.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2zhtnxvkn.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2jzgwmrmd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gt2vxegbgpf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2cefxklcq.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2djetdxvw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2wgpktbxq.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gt2odvqhdxu.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2uobhtqdy.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gt2qtinwkor.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gt2lloshxqc.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2mpnzomld.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gt2irmunzyz.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgudkkre.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2tysijtmk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2ujsufckh.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gt2bqqckkem.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gt2upejjnka.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gt2oqbfrebh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2uebnmcfh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2otpkkvvq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2dispmndd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gt2pfiyvpsx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gt2kimbrvpi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2ccuuxowe.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2xibzocpv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rostkmdn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2mjbxbiik.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gt2yhqcfmqq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gt2tqmmkdvg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2twjclecr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gt2alhrzazw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipzmrbia.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2notkpsph.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gt2ivsrinnz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gt2ornpxhbz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiuxfdqk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gt2oqhttnxm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gt2nyphflxt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gt2snszlsec.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rfbpehcb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ysqubygg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gt2gfngcxez.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2cfppqekq.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2iaiazfki.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gt2uzlyzlke.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2rpngqokm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2bnryktha.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2qcgeotni.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gt2eudkpfby.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gt2hwltvufn.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gt2yujmzjqk.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gt2iakwmtdo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gt2cfgqbxoc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2ggdtainn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2hllhwjln.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2amedqnel.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gt2hgmnjsmf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gt2gbznbker.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipnnhlxu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gt2hzblxyod.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gt2evjegppg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2ktygngok.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gt2gkwptytr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2msxegwsj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2kcnxaazc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2idrjnmug.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btjjjfqu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2aecxbdlp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2epnnxtox.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gt2qoegwhir.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gt2sdzaalmn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2cxkyywyd.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2jrjnavak.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2dmuenxmh.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ulipwjns.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2chwiieyh.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gt2qvzilbdh.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2bcozymon.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gt2lmorlsxz.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gt2oqpchhqj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2xluuoznj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gt2npdkoplj.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2cprpifyv.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2gwkfpdtp.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gt2isgmfmwl.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2rcksdhbn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gt2xxsciblp.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2pmncjmda.html


<!-- 参考信息 -->