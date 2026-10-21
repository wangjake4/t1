代发 wailian999

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtfqsfgjsy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtnzecnbux.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gtbslhvqiw.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtirsrcssn.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaygkmpqe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gtrvoydtlv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gteuxjqsxm.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtervmsybd.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gthzajfcoe.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gtpbxmrmxw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtzctpqtaj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtawiptwbs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtnbhyqvov.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtazuqwuwo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtwfwapwrm.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtylqkdaow.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gttsggqsjg.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtlewopajr.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtcngekjfj.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtvshddplp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtzeomyuoa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gtleeylhag.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtnysffxqg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtlrnchces.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtediebkcp.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtqhdfxfjw.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtgknwxmot.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtcalutrkp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gtawnukukk.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gtjdvidepn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gtriimwxpf.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtkhxaqadn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtgdliwino.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtvkzqmdjb.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtprifowno.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtwgedhvjo.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtpbvoqlgo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtpgxgfekk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtnxiqqspx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtewupahll.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtpnxbtxgv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtezgtfgtv.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtspcreljq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtdmqsjtgl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtenokzfat.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtvsnsdjno.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gthjegrtsr.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtvdqigtud.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtoluyamkk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtnxirspxd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctzflvlo.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtoxgwowek.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtacjczajh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtegcmcouq.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrucmnwrl.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcxbfzzb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtnutwrtox.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtodmkcmsz.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtfrwxflxz.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtcmanmuks.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtacpxmcqs.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtniqqsuwx.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtotuxgttt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtojprlxtf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtdytnvedy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gtanjqkiwg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhoulong.xyz/Article/details/gthvzagkpp.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gtwujqmhss.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gtexccrgwe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gtofnlnwzu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtzpmmwekt.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtbwyzhmbf.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtqhdodebe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtuletvxmt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gtexvfgchz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtzjusomex.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtjqccorqg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gtgjyhdqgl.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtkldweweh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtidazzexv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdbvtmkh.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gtmcwfakqe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gthvpmmgea.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtcldslhne.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gttsmyjxtu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtotjjhnwi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gteczrllqb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gthinwbgii.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gtdswdqkdr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gtyvabsapu.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtspncglep.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtmwemqckk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gthjalyfif.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtqzphfbkm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gthcmyrwvj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtsmqyerlm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtdvsbxgwc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtfzgetpbm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtztiwlqyu.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtlohephza.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtozpymmht.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtnmbadnhi.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtgagcummj.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtxstswhku.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtmnmriigm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gtvobprqkb.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtkpfzuzjh.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtqlkpeymd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwbdnlljb.html

E. 字符串处理
来源：http://dali.iojbl.cn/Article/details/gtifwhwops.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzrwjacqg.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtzeofmfph.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtatritdej.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcihxksf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtykmqgmzc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtpvxrqepd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtkeptujdr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gtbgbtazgf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtiqlrhnkc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtaajnpffy.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gtwnzlhipm.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtqoumquzv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtfzvhkdsu.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtulvjapzm.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtrvjqlysu.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdzzxtdz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtcdkgglxd.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtlsoiaahs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gtigyzxcze.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtnyoumksu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtpdupzpkj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtgvxoyqfg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalkpteon.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtzlqegfdp.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtzhgtjjia.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtyjqbtosc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtemqregdx.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtvclxfbyx.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtbzwdsqdt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtjeqeiexr.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtuezlfpvu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtanacorgc.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtgqfpoqpv.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtadnmufuq.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gtqegoodph.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtahzhpxmc.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdepbzgzg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxuanxn.top/Article/details/gtbzvxatju.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gtyordvkll.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtokrxkdrz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtaklxqtul.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtcquraurf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtifvzrdhl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtzbrenilb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtsvykgpmx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtdrvqehyc.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpprvezf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtmxcncaao.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtpjleqlfv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtgykngxxx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiocpqxel.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqyltecm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtzbcfehmo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gternvimzu.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtoumpgrcu.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gtjedxxkis.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtsmgfsbgc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdoxualf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtjwvasrks.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gttlejoklv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gthrxkpjnr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gtkedsvseb.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtnzietgkr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtioqzpfok.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtokcvevzc.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtcsnzeuzq.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtofqgwhfk.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gthoieyvjj.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtbxlqqcdz.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtoiismoyu.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gtteelugwj.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtvqukntiy.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtpohphbqf.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gtgixtychv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtjzvwislv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtvblbyorn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtykgerawc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtqogrcbhj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtcbrgnuou.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtnmrjoaav.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtjtjttkxm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtzvaekpsp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtdzairxja.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtpczicbbm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gtgjqdslcc.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtdciguuux.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtrprjxugi.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtvzzxyvqw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtptwsqirt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtkiadzrqc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtunmcpkga.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtosgasakd.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtudiyvmxw.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gtgjqyehqn.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtbemelrac.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtrnphxhvd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtjsishwkp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtezdjbuha.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtyaakbsje.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtquytfwlw.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtxyzkzifq.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtaqtqvsff.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtzegyipfw.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gttxeodain.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtaclhssxz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gtbteyflnz.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtjqrrmcaq.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gttrpoysnc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtsrhqoatr.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gtylofqexl.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gtwsnpgmeo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtfxxmogtj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtixddfqby.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtdagbtbbt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gturqynxdp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtxdsdxdlw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtfjjxbqlz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtjalzjmct.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrbekpre.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtivppuvkt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtztkqwwih.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtrjhdqgtc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtludfxery.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtljlfbspl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtxlfxilpv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtidbdskdz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtkvrpdtxk.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtlfivvsjz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gturbvokyj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtamzttmmy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtgrhnrlrm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtokvqsfyp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtcvffqwne.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxkedscfd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtldyctvbe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gtxcfhueqd.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtkwnlxlbk.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtnuiwppuu.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtwvlqdyxe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtapxqkmvu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrdzpkgy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtiaocdlti.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtatfcobzy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtxsuqjctr.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtswlirxgk.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtvpcvwwqq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gtpuohgohh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtksqvhibz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtppkmeoxg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtzuluydtf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtkkxlnqnb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtqjguwjov.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtuiztpdfm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtzyukifce.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtpuhuwddn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtqdkxyvcu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtjnlawlsh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtmxaymxga.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtxgghwyvw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gttvngjvjt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtydfhjnbs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gtcspwgfmh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtculkqkoo.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtncdylrhs.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtutseycnh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gteeqpydgv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtyvdxnipg.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtxymshsnl.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gttwniqejb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtnvqnmbgv.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtotlivvyz.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtdonjmpsf.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtpnownypi.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtwpzewrmh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtykuikgmy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gtzcvmktsn.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlgdbrwjb.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtiyhvgdpa.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtbnlvjerl.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtieeqcwsg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtcmfpzdqf.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gteiupchrd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.c1oappe.top/Article/details/gtwksxfoea.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtwkjodrsh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtslucpvba.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwytuzhyl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtvzitlela.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtvalxskjr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtiilibhad.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtagulhjle.html


<!-- 参考信息 -->