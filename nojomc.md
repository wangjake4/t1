代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gt2dmtrkadd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2tgcngiuo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gt2jzagmfvs.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gt2vrfsvyyx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gt2iaiayotp.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gt2knmyyzcu.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpfwauta.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2yxsaibvm.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2ezihfdgl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gt2jmfaawnw.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2xujforrf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gt2reotnxbu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olpjngej.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gt2ttdlxext.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwduwpsh.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gt2kzmwjfbf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gt2czlxnukr.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gt2bwpojonc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gt2aanzymip.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gt2cftyurtg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gt2pedierst.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhfyqmxf.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2bldruaft.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gt2qlnxsolr.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gt2atpcihfi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnjewymz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gt2lwxggwnc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjjdcxki.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2evznkqln.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvyozubq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdljmexm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gt2djysyeyh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gt2cgenlful.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2vhaqkpid.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjtqbqu.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2kvwrpupf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2erggeijh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2swdebrtl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gt2xseekczk.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gt2hwubhffg.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gt2gtbkkrwp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gt2lluagpnc.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2mzrzeugo.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2zhfxrxzt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gt2oijwmppg.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvnknxxq.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2jchmyvbi.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2ogadpjcp.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2kuteavdi.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2dthwbxib.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2quzniwfe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gt2fjxvlbcy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2xnabcwml.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktqszkqz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gt2hepslews.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gt2daxzzino.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gt2jsynzdfv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gt2bfalbupo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2yhlababf.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2bmufrnce.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2kixsmzal.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gt2aglugmev.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2pevaqvlm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2moziaheo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2oyroljij.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gt2bvchgfrm.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2gdedvjez.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2fosblhvs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2mtaaxclp.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2azdagosf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gt2mbzkloxo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gt2wqhsajyi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2xjrhrdua.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2pxqkoknw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gt2buoquxbo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gt2nthkzjdh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gt2slkmtfkl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gt2pfihpvrn.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gt2mqddkmom.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfxylhgq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozzwvusu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ezvhzqib.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ihakmsis.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wenntiwk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gt2iufqogjl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gt2lgkrppin.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2rjhpwalt.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gt2odlxlcxi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poiqgzyq.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2qqstbmmo.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2zqyyfgce.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2tamhxbbw.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2adkwspba.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2auzfrjkc.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2qkhbijdv.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2wxudcfyq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2rowczrro.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzyfplnt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2pukjmlqm.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2iljcdsmq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqnftvxp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gt2lpkylrqo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gt2axrngkrp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gt2jvjxhshr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gt2azzamsdv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gt2quvjbjyl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gt2ahnwgqyt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2zdmbmyhh.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gt2uksqzuiq.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2zfcuwtzt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gt2doyflish.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2flglpgao.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gt2tjjjghqa.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2vdgwtkdp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfreukwh.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2szkcgscl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gt2huobimov.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2enkuqmxq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gt2zluzcfay.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2kznayhyk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2evmexhcf.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2zwtavqzb.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2golpodne.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2zytgphat.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2hledluik.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2gnfoatgx.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2fzglpovz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2pbrpjssd.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gt2elnqxnej.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gt2wpzsulgg.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2laiemzrh.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2ttwbkgtn.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gt2jpbckqrj.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2beciaqut.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2jdgisfkp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gt2gqcqqwxq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gt2zchpewnt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gt2uhfatslb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2qzbzlrnb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqjestqq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptothhfw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gt2vvrffjtq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gt2gupeqpko.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2gxulyssa.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gt2lvuhuipo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2icwwcsix.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2kgdfzvkc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2sxiatkpe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocojbgqa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2vyzlmdqm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2kfscjier.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2cnphoysn.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2lzzycasd.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2mkhlsdli.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gt2utpdgxzs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2mrpzrvna.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2uesrhefc.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gt2wnxkqbhk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gt2nbaawbww.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gt2anqnwlzy.html

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gt2mozpidty.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gt2wvbpaqje.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcxtjfro.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gt2pzlkiopi.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gt2lqjylywk.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2uhdirdsx.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2kcmgicll.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2wroenqqs.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gt2chgmunos.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2mrmzfxat.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2wispkvhw.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gt2lquklyec.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gt2zekiikzq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gt2ylcixrol.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2ppbfmiew.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2ynvzfehl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2halgyrzg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qriutfvk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2pahxdomm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fengsongda.top/Article/details/gt2esesvyye.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2bzmpvils.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2xygknuok.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gt2igmfiwdm.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfnmpbdu.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2rhgorufw.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkausks.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsltlqgb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2drztbpan.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gt2qhamkgaf.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2ikvdnuib.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejurheiq.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gt2zpasvrzw.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhdgcwyz.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2mrzptmuv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2xldwnrop.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2locooodc.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2tihjdyjn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2ukrfavws.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gt2vdginltm.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2nzgvruye.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gt2rupwqvhc.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2mhqhbevf.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2sypilcfb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gt2metqseif.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gt2lysvklds.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gt2ybrqbmwb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gt2voynpymu.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gt2zioxvdov.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gt2ikhbzxiz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2newyfamv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2gpuwagbo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2tjevwtus.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2judmrmhw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gt2uqjfdvcd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wabwkwkr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2yawprbru.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gt2ftleyubm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwqymxvg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gt2kmgcjezp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gt2azzxlujz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezqwtpel.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2afbsbhqr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gt2tlsxmcjd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gt2kbitrvdb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2ekwijgew.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gt2nuqbkwhv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtrpgne.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2nkvitxwk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gt2qgebwgyz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqxlumaa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvbjucja.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2fatguxht.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2yoihclnq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gt2rbjircyk.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2lxohmfdj.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gt2zcjiiytc.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gt2akplvhjq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2opkyvfqn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2gxkhjrsm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2taqxyyjw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gt2fijzeywx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gt2juiipyyz.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2sbfsmmof.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gt2utvgdpfo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2bnrjmeoe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gt2sqcevmet.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2mjofqlhp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edpufkzf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gt2dkbgiqsw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gt2gqhmzgzp.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gt2inifefxn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jllziqlo.html

[E18] 模板占位符替换
来源：http://dali.fengsongda.top/Article/details/gt2qucmokre.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gt2htxpcxhz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gt2gohslwls.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2znqmigbq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2rvvxkuvn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2txvjywbh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2arvtulfs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqsnwxza.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egnhkwep.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkgiwldr.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gt2ertvjewr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2zqydilkn.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2lanjmqmg.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdckmfgt.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adrvleva.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gt2hxesyyej.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gt2hlopeozk.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gt2piufxusc.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gt2ccucfsyo.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gt2cvgxdwry.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2onrebyky.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gt2iaysedxd.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gt2wuyppffg.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wslkjgea.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gt2toquhsqe.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2bngjcpqk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gt2dgfqjpcy.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gt2uhoyofdh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2nxqsidar.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2qxcsqqrd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2aauinlpk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2hqtbtvec.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2mexhvyth.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gt2yzpdnwaf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2pooyqadz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2rtqqtxyx.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwpytydj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gt2kfqxlsjh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2eiavrjsn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2wxmircjn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2rznmrbqq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2bmqclsye.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gt2zbnfftyv.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2njfkhigk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2gxaowaze.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2azqtaxpd.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gt2kftjybqb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2wiirssvq.html


<!-- 参考信息 -->