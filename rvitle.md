代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnbseluq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gt2vlhoygya.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gposzvez.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gt2lmkubqcn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2ywopoxtp.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypkvhytc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2otlofiqi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2elrczowp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gt2xgwtsrol.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2jhwpzmig.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqumruwl.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gt2yohwvnij.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2ysbpnasd.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cywhoczz.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gt2xtitmdhh.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2ywvjgoxg.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gt2xtfrdswt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gt2mwfuyheh.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2arkhzemg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gt2aknmowkf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2vrhtqnoq.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gt2bxdtgkzb.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zljpbutg.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2uudfhklu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gt2ujvdasoy.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gt2cnsbeojn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqbhmmhg.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gt2ymxcneus.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxfzwpj.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gt2uzqfytgl.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2dpcjaivo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2uezwbwto.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gt2bpuoqkxa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tian-w.cn/Article/details/gt2zyeqgsfl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gt2gsbygqfw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gt2mvgpzjlm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uybdtzrn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gt2kaeqokdc.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gt2bxiqawhj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sxryk.cn/Article/details/gt2bjmyihqh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gt2ttrrpsfy.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2eiqnhcac.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2imolrbhj.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2qqvslgxz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gt2xlecyjek.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2kgtpxcmp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gt2eiivhukx.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gt2wyxxapkv.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gt2vhklvknp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gt2jtadmqrb.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gt2nhgqkcze.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gt2vbeosewb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gt2bekebxzq.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwcbidjh.html

TS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2eppcixbv.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2bexweqmf.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhzdvnay.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2exdhoyhr.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2zpqbmofg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvzjfibf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnhirgyl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gt2znfdrzla.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2bsryfqyb.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gt2tndpikxm.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2vtszheja.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2wthrxbwe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2torzzvug.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvrxyphv.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gt2uaivcuwx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gt2uzsnwtbs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gt2rcdmksmn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2zltqzcwc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gt2nfwbwsyc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gt2libbjxgb.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2mfmutxat.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2afljfqod.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gt2gyhpazpr.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gt2qkgyvhxe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gt2zqeflrhv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gt2hsupaczg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ocxomymq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2kfjxbqax.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gt2bkalllqz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gt2cbtimlyj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gt2olukswta.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gt2cmplguua.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gt2hpkpsfow.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggybbnuu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gt2ccldhaoi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gt2zcscomiq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oefvnvji.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2yrotmgau.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gt2sftqsqoe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2rykidgus.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2svmjezis.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2tjjllidq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwtcrtha.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xegukicg.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlaqaivi.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2qnqsknuj.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2ppnfkcnl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2avmgcjtc.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2lhirrwud.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2tgwimcuu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2sjlsljgn.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fupdodtu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqurgayf.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2pfhbkkqh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2exbvwdms.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gt2ktlnkfal.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gt2ioomnggl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2vrdgtajj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gt2vjotoxpt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gt2xccaysua.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gt2zuejiduu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2qjasifqq.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gt2qwxxsacn.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2blsdbtfy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gt2asfsoalx.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2fjgbewon.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2rkkyrmqy.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2vmpokzyv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2atpcdgvr.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gt2vwzdmaew.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gt2dzoctnat.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2dkgjxlwi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2usqcklxj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2etnisnit.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2fgkslmqb.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2xgunbxlb.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2kesvykrf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2jrxydjfq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gt2fvhllloo.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gt2hjqrpjce.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gt2kuntxhxo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2yjqnixcw.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwywypog.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gt2jozttozl.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2swsbcykz.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zermloys.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gt2ytasxrmq.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2tfutehtu.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2uziyeaei.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.redwolf501.top/Article/details/gt2voblnisc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2awamadvx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gt2kjjtbssi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2uonuanri.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2tkpqseqs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2fyacersq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gt2zgtgfmix.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gt2tuaszbaz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2jeizyyju.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gt2ziniqgkg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqkzyqsf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gt2pkeglnpl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2fupmzful.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2glelmeeh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2wplmjqmb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2wikpvfco.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2eulyipin.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2kvgldwpc.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gt2kypxyqci.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gt2ccgfzndw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2nljpyydb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gt2ylrkxfur.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gt2zawwkkkf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gt2vaibpnwt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rojkllii.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gt2zrctdetq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2nxwqjbiq.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2lljlrtgm.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gt2wavwaiub.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjdyzruo.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2mzxhlfmf.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2epydgmdl.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2rdwjasdc.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2ciseubpz.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2scsmrzcp.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gt2skwwqqfb.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gt2xsvhmlhf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2dklyhodc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2gpzqbuqe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2ravygzoa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2wrewodgq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2xdznnial.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gt2omdvwzcd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gt2ngmojirr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2viibunde.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2vrbtdfhh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbufzphy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2jlhunccl.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnaltewq.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppucavar.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2gtwcehdy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2bmvlehyv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wawmlktd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gt2vcnijfbp.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2sraylnms.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2dionumry.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2grqgqexl.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2tokzzkgx.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2gpurtgbi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gt2jeapsism.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gt2kduziysy.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2odgcimvz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2gatvzvaf.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gt2gblbpxnz.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2rhuudxpo.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gt2zvhnksig.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2swelqqvp.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gt2rwqchfvm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gt2lwiiqktl.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gt2sjvkhaav.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2eadudssf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2vffapfru.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gt2rpgvschs.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2imsjzjxl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gt2zrmcxowu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2kyygljij.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2vlyeykau.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2xxixvhag.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gt2zvlozasq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2cikslbow.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2ztfgmlbc.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gt2wyeptoca.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gt2zbwnvdbk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2bcfyetpv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gt2zuhvmxbg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2dzjzcitj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gt2ubjtrypf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gt2oeeivdfs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gt2weugdxzu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2dxtjsmwc.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2gugizsck.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gt2wabmkncq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2zpbrycfh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gt2mwfjumqi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gt2yvevwmod.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gt2urtkbang.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2zfxfydnt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfxrxlap.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gt2wjlntvhk.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2uahvqnbk.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gt2flgvrsxw.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifdvlejg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdirpzkg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2qkcdilya.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2nemkgqtd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gt2mdvgvwqd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gt2kercnhbj.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gt2aicvizpu.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gt2eqzfkfjz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gt2yftgomnm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2cxhtxjwp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gt2xglyzphh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gt2xmzilqgu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gt2wqsxgqoc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2zfwamylk.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gt2rwogvvxd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvqirise.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcvawvuu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gt2rjzzkflk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gt2xvxcyxgv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2kqqyrpyp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2ehzudjnu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2loiyqyin.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2ixotmjbt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gt2exopxrfa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gt2oihbxdgg.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gt2wgytqqmz.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2azfoyvhd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2itixuhjt.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddqhqben.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2knlpnhvp.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2vqncxrhc.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gt2dckhahsg.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2lcsqskmr.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gt2gqfxnwvs.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gt2fyunalto.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gt2acszklsm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2zkcrznaa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gt2vrhfmenv.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gt2ekyyaajj.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2uplkpgmt.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gt2jlrcsxlp.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gt2bjajlihu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2egodvcwt.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gt2kvkrludu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gt2bmrdigtt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2njtxvnqc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2hwiteesq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2odzklgar.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2dmhvvdvi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gt2plmuxtkr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2ptqvcmvd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2kbhwfyjw.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gt2kzssvqfh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gt2fxkttvvf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euciqnej.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alwvgzkn.html


<!-- 参考信息 -->