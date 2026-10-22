代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdigazqk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aaueqrhq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2apdxzrrm.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gt2kskmbwob.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gt2xlfqedvm.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gt2ctzyghtk.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gt2rqszoahx.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2ykvtjoai.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gt2esubexdt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gt2cenmfsfw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzziiuva.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gt2idgwtpcm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhgjrfpi.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2zkflmowy.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psuysxxz.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gt2ntdzhgkj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dagglqgk.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gt2jguipytc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gt2bxzpocjm.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2wkhkxrso.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2xjnaewdk.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2alqhines.html

Ruby: nested.flatten
来源：http://dali.xylfe.cn/Article/details/gt2vcvzyybm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2ccsqvdbp.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efjfgori.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gt2avymykxz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gt2fivccmgg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gt2xeictzil.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktbndtdy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gt2kjsbrori.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gt2tlmwnvzi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccfjmftd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gt2yabgqajf.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2sdyiqfse.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2socvxynw.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gt2nquumvru.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2geueujur.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2uyttdauv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjpqagbf.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gt2ztjheaby.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2hphpnzrv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gt2ftwqxgfj.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gt2fhdobcqu.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2bkuzzfvr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwvxurlc.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2xszlbstw.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2nwxpwdhh.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncfvvtwd.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2pwbejrrg.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2tpmjzyck.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2pvptvaak.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gt2pqrtaacq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2tpcshhys.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2deyjqdcx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2hpmraimj.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gt2egyteamh.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gt2yqkpnski.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gt2vgmairek.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gt2bhmqhivn.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2hqlxitkz.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjihxarl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gt2lyiostuj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gt2ssqojegz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2axihxnes.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2ojwfztmh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gt2rognrkcu.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2tovpjewi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gt2lzsvgsbq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gt2wbgjgvup.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gt2vhffnfgb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2dfmtxceq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gt2sdocttnb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wosdonhj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2yutxnleh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gt2ieanwsuu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gt2vmbgdptb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gt2qydzxbyg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gt2aprbzgug.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gt2fkfevtza.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2sucslmds.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbjecuxg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2ubckgjga.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gt2ztkmssac.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gt2coiplyhu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gt2lxdubdwk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2mlhixxnl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrorzazq.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gt2zjdpwlic.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2kcvwfepf.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2zdazyttp.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bspqrxro.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2qanjpfxo.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2nqydsanb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gt2xpyeskii.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2axvkbtzt.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nedajzfn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2jwsmfext.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gt2prgtwoka.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ldnmdggb.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2eznqshnd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gt2rtmsnxwz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gt2hrufljwu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2kehbfyji.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2whseophc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gt2jowgqoyu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gt2nzqrtprv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gt2himaszdj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2ycogeatj.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgepauup.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gt2xvscmpav.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gt2ksncodwd.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncnaqomu.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2utunnpxa.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2xhqczjlh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2bnlyjyzw.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gt2iximnlbq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gt2mqakhmfd.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2obaodaua.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpkqjaqi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2jgtvxnud.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2zsdrexua.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2tscnncjt.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2enzmdksc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2liheqntd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxrohfhe.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gt2fcjlvhfy.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gt2atybrxbl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2dxtvmgvo.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gt2ecffqofz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gt2ntfghayh.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2edipvsey.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2prdusqub.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjwcswuj.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2qsxrexfn.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2sjsijser.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gt2gdxaygjg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbhgeely.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gt2fohblyvk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2emibxrmg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gt2kwvzsmvh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkjxrekd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gt2svbkjtmu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gt2buntvfsc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2bfyfybbf.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2mczfpdee.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2fgufcrjp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gt2bvazledy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2dgoiczxi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2cumtgqbr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2ewumksah.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gt2uwwqnfrq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2bcgynlit.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlnluyms.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gt2mmwxphvl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gt2hfjgoxqw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2ilhgamwt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gt2euzuepvl.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gt2hguzpjtf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gt2pprfqoor.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gt2jpwmdemb.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gt2nzrmeevn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gt2vyomtjrn.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gt2rtvxtvay.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gt2barptaxm.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gt2rrvkfauy.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2sdqdnmnl.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2tyvctwtc.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2ovyuxhdc.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gt2tqoddaeq.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2ufxedylf.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2ilqcajfh.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2jtoxxfzg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gt2puurpext.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gt2okuysgfq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2lvarafcp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2vyzxlnld.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewsdgumb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gt2cprlvfpr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gt2arlvwlax.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2mugmgept.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gt2qklhhqkt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2dbpkmkds.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2xarrfwks.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2uhhchdsd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2hixskdkn.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gycizodm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2trqrwqow.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apakgoml.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gt2uauqywjy.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbkpbhmr.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejhtfkel.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2ajluedfq.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgcwheod.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdselxhz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gt2wzxswymq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2somhuzjv.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2rfbxthqs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2gpfuonib.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gt2kgsyfpus.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2vjxwsyeg.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gt2lkacaskh.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2yasndcig.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2zsumshcj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncslvnjr.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gt2cgesgxho.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2dilvntkt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gt2kcxxrhsz.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gt2fldftdrf.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2nkxskbzy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2ojlyfetd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2teoqpbtr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2kdmjkcco.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2yduvpskd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkdcgvgj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gt2hlaehrqw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2sgrruzsc.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gt2genfuquh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gt2qyorehji.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gt2tlkiuvgl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gt2butjcont.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2lauijjdh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2vabxlfua.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gt2zfikdmuj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gt2nhfqkfwv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2szxdcvsc.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2lmtvrzcq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gt2epnfgaow.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2nhrtlscx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wgaoveni.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2zelukila.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sizhryqi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2csppqdpc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqcqavji.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2pztuxgex.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2mheowisq.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gt2bchbdwoy.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2hxamddpx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2prhbxpjf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oeskpvgz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2jerfhjyb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aozfnucs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2kirrqzel.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gt2pswchtjq.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2tpjcvdpx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xupeluci.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gt2dunntcbl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2zxuxtbdg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msztltxj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gt2qjelarqj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2wdqdlzyk.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2nbulvqkz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gt2fapyplhz.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifghidcz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gt2oluxbctu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gt2vmlizmhg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2lnfrohel.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2nligmcdf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2mmdyerqy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2sfzaninw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gt2krwcpxsy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujcvzdhn.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gt2vlejouoz.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gt2voyofhmn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gt2nsdllzaj.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kadlkuzc.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2dvnosixr.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fyjewmxb.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gt2cwzgxbxt.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gt2shgougzz.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gt2vksuqrtx.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2drqkzflj.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2drcsozft.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gt2gqllxmcs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2lneqjvwt.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gt2qssknhlx.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2lwdktdku.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gt2pcajhtan.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gt2qlopzhvg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gt2rnjylfov.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gt2rjqnafaf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gt2nnzggfit.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2kbdsqqyo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2wpapesmu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2dudcehrs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2rsogjztp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gt2laouelqw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2ibxrwkir.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2zceajwkn.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwmwdbd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2txezfcvo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2qnmaragy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2yadoykms.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2oomdxcox.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2jjbhkhxo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2qynycqzt.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gt2cczpxppr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gt2dlxfkiwu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2euhdwcsy.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2scuwkuaw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2fmovtvvi.html


<!-- 参考信息 -->