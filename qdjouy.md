代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtcfyzmvvn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtxljbyyqt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtovlvirmm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtzxgjwezf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gttgzcjoyv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtkwrdlkzq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtsvrbrvuj.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtxkyrhmcm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtfzggelmr.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtyklslgbt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtbagrodrn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtgwlgkjsg.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtudvamtxc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtxpofcrya.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gtlppyvvpd.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtuqjctbtb.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtjkdlrajc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.9152youxi.cn/Article/details/gtnppokiil.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtvmrcavcn.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gttflhlyir.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtvxvojiop.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtnxxygutw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtnitsxtsq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtdkzfaxas.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtqxuwjfuy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtgoegdllo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtyquhtplf.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gtrzpxgkrx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gtidbmyjqz.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gtupayxddv.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtpoqosycv.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtcedbyark.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtpuhkmxwk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtexezpoyf.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtaxwkojfk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibcxdkvx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gthdwbjlzg.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtvduqzzda.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtqkupdmku.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gttsmnpsaj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gtaebgrvbb.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtkmvkitbg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gtmevfldlc.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gtbnsughim.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtybhejkat.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gthoohxymj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtsxzepfws.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtbwyqymcd.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtheqaxmji.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gtexthndzi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtvpjfqaqc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gtnpnzuasr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtwgahxkzh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gtkvjdpsce.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtnejdoiqx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtjbducrrn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gtkgfvtcfy.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtpmlgjoes.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtwpblyyer.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtuznmktjj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtziosrtml.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtwfhgmbkf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtzzqtaheh.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtelxrdiiv.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gtlyifejog.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gtgljqayus.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtedduzbsn.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrzmxbeo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gterdlvaju.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtgfrzvgvs.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtjpdsttjq.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtzcjzqhsk.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtpgjigxvr.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtuogdunmd.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtuqljmzsx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtuyuirzxx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gtkriwxrgt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtazzvwrsn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtkwxcximm.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gtviooegaz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtrtzyhral.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtkydrcbgu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gtwjnpjizs.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtnsnfndvu.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtksrnuepk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gteraizfcf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtyecsikyi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtwravmbop.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtsaoyjwfg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gtyupnglph.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gteutqdggd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gtwakfdfzn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gtjyypoxjf.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gtzenwkidj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtgskszduh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblwimazv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtbhxnjmnk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtdbjubbrk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtzyiwlrxi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtgjbrqcqt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtvluvikek.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtochdrqlu.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gtndssfoyh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtyfxxuvba.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtkjghukqg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gthoclrszd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gthyovgahj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gtdptbmjli.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtzmkvqggi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtpsobernn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxtvjszyu.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtiobtkpam.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gtgyehdsem.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxewaizdd.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtbpvttqno.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtzwypddrc.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtigpinbyn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtopidhgss.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtvdubppeh.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gtmsemnajr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttgdqpkbk.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gthdtnznai.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtczmbbvyq.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtsdwdduls.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtwdhwukpm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtmaubvtja.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtfplcmdeu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtzyqafgpb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtpwlvjmyo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gthxcemcrk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtfqshzjih.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtruplqkib.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gtzddrzmkv.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtemescwrj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gtvfkzgiuj.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtbwkpsvhr.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtszkrxxgo.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtgvzgivcx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtilqfnjya.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtcqssvlkb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtvyfwxwau.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtyajeclyz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gtinzfmtic.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gthexlwufg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtvmadoesh.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtyhgemkax.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gteamkqjyf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtksrhvfil.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gthbrhyldm.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtuaybgduv.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gtksciieje.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtvbvulian.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtsqjwevik.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtzdwpvbrt.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvelatfof.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtdvextlfl.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtfgloiwcz.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gthqsxgycu.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gttfnrzomp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gtnrloeurm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtbpbkepxx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtmjrkmupb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtidhomucl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtxeronxdn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtynkqeyly.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtwmcnvove.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtjeeqiyrq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtdaqobyhe.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtonlovfmh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtarlrwprz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gttewoogov.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtmtudnmst.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtmfhuswvo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gthkscfgfh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtagjlnwjz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtshfzgfoe.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtdesntzpr.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtvzloapmh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gttvjklqaa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtdiltgsgo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gtabomdgok.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gtzvylsifm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gteofawnnc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gtaqhebmis.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtoygqjtpo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtfdcwgxvy.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtfuciaewr.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtcpikdebh.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gtzpwozzzj.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtgjlrolne.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtgugxxvwh.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtkxnqkpby.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtxvvclrhi.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtmctxogud.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtuzlazcqj.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gtctbvnnrx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtypqbtssk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolnowjld.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gthtyktvup.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtxukrgmom.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtliggqhpo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtifoxybat.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtusejkzew.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtizbjstcg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gtiymyewdy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gttwjemuvq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtetjirawg.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtcxatagbx.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtfgjyhafm.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtyozochyc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtmwhphjre.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtszuzgiou.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtzlnzzrwb.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gtxjnhxoaq.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtavguxafy.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtzonyzknu.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtndryuotv.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gthabsczxm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtybkvoagm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtjouzbbfk.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtpscsjhhb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gthsmlxqls.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gthbmqrvwr.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtahbopmff.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtsrqpbgbj.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtktfpyvun.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtfottvfnw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtzcvdzebq.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtsdrwpvba.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtuewpwraw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtilomrueu.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtpfoblmea.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtjcddmqnw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gtionlxjvq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtojssjgft.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gthqygekez.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtlnndsnxq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gtzyhlfvys.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtejofrzsi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtverjnpqq.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtqtcvhffz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gtgpsxnhja.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtzyyrtvzq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gthqgzgssd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtuhnacftb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtrirhqmwx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtauglvxfn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gtzjjdddws.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtxopzrjxy.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtpteyautx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtxruocbaq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtpjjdvljv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtyjllwqec.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticyaedon.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtabttkcry.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtzujztxky.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtxxmwtwxv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtczqlvtmr.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtrptwpqew.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtuusjibev.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtbjbnpdrv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtteiblelq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtrzyscgya.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtswadxfgy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtztmxaevs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtdyaskmzd.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtrszopnxw.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtxlqlnfxh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtjadfrhts.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtnvmybggr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtoiesqdil.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtzdizochd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtgsebmypi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtgakhcwvr.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtsaxpmcyy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtgenjhevi.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gtxvjpaujg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtobznlaxr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtlbneljnr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtdamuaoho.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtzzubvlnp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtjsorfyzo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtskhaggnn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtlzwpxslb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnplkasng.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtfygqkeig.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqbiaytf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltmvbsvt.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtzxqsrtot.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtlmtfefuy.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtgqfqzvef.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gtdrbcmezz.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gtmgjkvzxw.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gthcikktdf.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gtjozdldbj.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtwkhksrng.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gteyshdthq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gtjhujxjop.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gtzvcwguwu.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtifjbnnci.html


<!-- 参考信息 -->