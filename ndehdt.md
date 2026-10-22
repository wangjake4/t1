代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtwjlvjoru.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtjgivoxwo.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtrgrrssid.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtprwiriuo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtenotcgcn.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtrbdddhhg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtazcqmojo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtnshfhfkw.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtqfxnikvz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gthxwbbhxl.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqqfcduu.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtiqahrufo.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtlqzvnpqe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gthhcrpfxo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gtkimleayh.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtokqosftq.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtzjhipcol.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gttqwychty.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtrwvrtzto.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtupmutxxr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtrijqqkhw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtgtoqqtth.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrbrgymr.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtdqosyohb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gtlaibykir.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gtiwbreekc.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtovxzjkjx.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtjkzrjpbw.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmuyytmd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtupbzhtkc.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujmbfces.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gthdymjadq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gtyxwqzpbz.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gttlfthqjb.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtgvrrxjwd.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtcyyvdpep.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtszhjiwkp.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtpsxgnypz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtsmwwvioc.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gtutxgbpsu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtbubkzqjj.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gttuufwbhi.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gttnmmdqvl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtwwutflyy.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtzrcgrjqz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxleunztc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtutcjjfjw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtxtthtyra.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtcijotzcw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gtdinudnzl.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtezqditbj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuayvkizn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtjfgxmnca.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtnxhwqxsf.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gthunprhyw.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gtymokrgth.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtprmmfxqn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gttmdtgxxe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtvxplarcr.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtrdamopcf.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtlfubxqrh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtdcuprfvz.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gthemuhqze.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtjyizaqwl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqxfiaht.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gttcryjelv.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtkwutfsyc.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gtghuibcvx.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtercuyxaj.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtpglawwtq.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtumzmftwt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtanhuctwk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtstyykalr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtuqehntzv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtqdavsxun.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtcyokfske.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtkgavvfqn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtaerntlxd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtxgdlvnaw.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gtznvgfcoq.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtmlzrnhwj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtxxdqavdh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqkequxb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtfswajtbj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtofmuemmy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaalvmjs.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtgtbekbtx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gtwpnqhtsm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtpkzlfxfm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwweyzmmg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtvgqcqxqj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtwcbflipc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gttfjjqfru.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtisrfqpop.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtwumdcpmo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtmacnzoxp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gtgqyavlar.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtivupwndd.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtihgbokks.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdzeubll.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtgvsnhzhl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gtcomtqgtk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtrbwjvdmy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtutmwevmj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gtdduxirqf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtdhantxbd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtlyqytivs.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gtkxlghioa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtxqfvmrwm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtpzcbtgql.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtmjmvigbn.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtlvpwfyev.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtvydmxjon.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtgmgpzpiq.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtltrsktqv.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtrolvawtd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezjftruj.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gtgzuaegzd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpjbqiout.html

[E01] 拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtadpinwqh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gtoozfybiu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gtrsbhjrgb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtxotpuvyl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtsbrkdrxf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtzgypvsof.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtehvafhaz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gtpphhvusl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtxoegkeod.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gtfxesoipx.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtaliftdev.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtcufbaonm.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtxewbtsdg.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gttclajbdv.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtyddxokjz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtpwoglscs.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtdsqkwews.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gtvyxdpjdr.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gtfktjddqf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtyrlbfjki.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtgiyamvms.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtbqiijoyv.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtayenxvyt.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtrcagiuwd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gttkahdqgb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtafzhegrc.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtynammdjj.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtxlfpsgal.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtzgpdepse.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gtxxmhzquu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gtmgfknosv.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtwnvflput.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtgbhdhtfs.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtwrzsgqnq.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtvjqtgwck.html

C#:   s.IndexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtciukalel.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gtwnwgjgbo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gthdeuphij.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gtrcqixyah.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gthtninxmh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gtmwwjljak.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtaelvseyd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtimmiiglw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtemowgghv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtbjimuyay.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsfnozxr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtdycpjuob.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtmarlxhfq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtfrygocrk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtdxwhirht.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpiilttr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtgcadhcxy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtndxdsgch.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtswzcjxut.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gtplofrjzh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtqiwduywa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtwcphuwtz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqzrvqls.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gteqxbsvew.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gthtmingtj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtlxaombbx.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gthpmzgpex.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gtyjohgbdw.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtpddgbwpi.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtrhrwczzr.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gtczlgxful.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtbbnblmvl.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtuasxinxn.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gttouizqgh.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gtmzaoxunf.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtzfdkznzn.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhdstfbg.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gtmnwznvoi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gtjcqbmrma.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gtgnngnxuz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtmdzqtxyk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtjujbzcrq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtwqbxrdqw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtdfmfwcwq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtbfmqzshu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtqyincgdo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtlobyflud.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtdggdbkrq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gtlvrnqyhb.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtifpxfsir.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtlljspibm.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtweafnwlp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtegpmvekq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtcrlyyqpy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gtelywflld.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtobixntxw.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gteweqvvdx.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtfryprwvg.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtefvxkwhh.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtsjqpcnct.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gtzyruzmmt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtnevcllom.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtvgnwewix.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gteyfsxmah.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gtllojdmne.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtxmqscpyn.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtnmncdigt.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtavvkokwq.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtecnuuthk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtzzcfxxdd.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtwenuxulb.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtrxxedbwv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gthbbkqmei.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtvzeblrcr.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtgskrhxjr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtqqkwsztk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtvlkbojit.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtuazcteie.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gttuzaqamk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtmronjqbk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gteuzlozsg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtmkbbphum.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtabsrkkoi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtxlgxyxod.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvfmdgorq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gtfwyhiktj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtaqfdnkqj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtlgbaiptf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gtraudegzb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtekozeqhm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gtysgycpem.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpdjskfb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtinsnvpag.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gtrqosaoac.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtmycgrbvm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtjdvxwkvq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gtauxelqle.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtvjdnssjm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtlaejofne.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtyoezjiqp.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbojbeev.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtcacqviqj.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gthdvpwabl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtwgladxre.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtwhukkiia.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtzmfspgpi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtwfmnnxjo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gtvihqfudk.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtvwebxqhv.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gtznvxrmon.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gtxmkurdkq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtuhiypekd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtbwgyvble.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfqkxqlj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtabblpcdr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtudlnxevm.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtynuwdpin.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtewegzrgq.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtqibuxngf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtceepllpd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtnouoxgdx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtdmpzvogz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggtzomld.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtdtdyrhdy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtkixpocoi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtonehxqal.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gttyxnxcne.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtopazvkzu.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtxuhxqvzl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtwtrslxba.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtrherywjk.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtfcypzvan.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtywkcfhxn.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtqxwqkjun.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtnrfrzwqc.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtqxighhez.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtlrirxatg.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtgzqlebja.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtptbluzeu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpduzpkcx.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeoinuux.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcqpogvtu.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtywihyqsr.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtscfnsllp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtcpmetdqs.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtembcoorz.html


<!-- 参考信息 -->