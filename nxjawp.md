代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtovgoffiy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtoasyrioq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtcimxcqav.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtkzvvyryz.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gthvtblffh.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtemupuodc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtwfwioyfj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtotwdydar.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtloaglznw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtndvjutbe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtgrepsdyv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtsyqafocw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtajgtoeau.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gtxyyiiwnc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtvysixhmo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtzmmevngf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtjlbqcxca.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtduvrfapu.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtqcjvfema.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtekkhmgnz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtdntrirsh.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtyruaycuz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtyykghiia.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gtqhwjowth.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtbivcjamo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtqykjohlq.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gttuilolxs.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtssgezxkp.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtysufypuc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyomyqfe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gtdgugglwx.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtmftjbjmm.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtrabrcjob.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtynmosztk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtyeewfyel.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtowqitnja.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtuurimwsn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gttgkkauna.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtchnligqx.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtiaeeolfq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtsdcqsgcw.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtwomwdxhu.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtocsrilms.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtfhhqwvfj.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtnkqphadc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtnjcqcyrn.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtcnyyfgfv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtiykeouzp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtdjpdsxmk.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gtjbusvjzs.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gthsflgmhq.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtorxanyie.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtgzpbbhdr.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gthbqbmncm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gttrdfjlqz.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gthustutsc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gtybhctpoy.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtwxiyvdbn.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gttyqsxadl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gtbdxnputr.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtabmyffrl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtmuooolot.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtcmejpenx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtpobwxklh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtvxviqmau.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gtzhhoetso.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtyxknwpfy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtrnceigxx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtvqtqalvg.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtkkxljahv.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtznnttrvs.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtzdmgbnog.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtlgaktaqv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtfutggpuy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtdtfzdrtj.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtkznwmihj.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtjhzflpit.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gthfxbepkm.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtreyymmqc.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gtufkmzoiy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxbelrxn.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gttoouwizo.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtkhynffrs.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gttqiqqetg.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtoqzfmoaa.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwnwsqyh.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtlzjkypbv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtymqzvdtz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gtbxyjcned.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtfplkcgzg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkiysgvo.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gtsogjthjz.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtuahqnwmd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gtosmgcrfu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gtqtpbgnpk.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gthtgwkbdu.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gtnqxhrojz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtfbxjuduf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtwsulvrxk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtrpcrsfvy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gturummvgy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtuchziodi.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtvnxiqkiz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtikoqbame.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtghvhiqke.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gtjjedjarl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtovwxcwxk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtgacedhpo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gteazheefd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtqfjaudln.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtzlswxbaw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtrexjpfrb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtljadqidz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtpcpludbx.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtqxtswnqi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gtttbhvhif.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtlgczwnfa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtettrgymq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtoogqicrl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtwbtvuscm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdsxocrg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdvtante.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtctjlimaq.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gthdibywbc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtblxlpuzx.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gtvzsygeiv.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtqagdnnkw.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtlqwjceyw.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtprupobmu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gthwtzozpt.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtkfbaqncu.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtpnvcxwgn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkxzbovxd.html

E. 字符串处理
来源：http://dali.quarkkingdee.top/Article/details/gtxjqbuvgx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkxbhszoo.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gtqgqkjqik.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gtsexxwvid.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcigeibz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtspjsawzr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtgoqszdcd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtiuqtqclv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtttlqhrmk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtatkphupi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtqtrzgeol.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtjdcwcpko.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtcsvojwna.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtrgkhtsqx.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtqxfenwvs.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtcobmogzu.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtmfhlhzlq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtmjmokbut.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtfmhovumf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtfazujaic.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtgbtdfwbs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtoffzclbx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutikslbs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtaveekrhg.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtnfxsqukj.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtkspncuqb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtalfmaxts.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gtrxhrjhbe.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gtyvciefgu.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtawhzsrmc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtzqxowvby.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtrkcmwdzz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gtbzjydpzv.html

TS:   s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtcdtjdtiz.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtozrgrnif.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhmjuicw.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtxttrakph.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gtuctzhhkt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gtsxixicrk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gtojkfnhgy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtfjavrrhv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtdbhgudiy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gtjlaurgvu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtnmqnbcpw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtsccotinh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtpencpmda.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtqnqdjwmn.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtjiymkond.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfpohgsyn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtcfcwepan.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbtqvpik.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtdqcbnllc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtiqkmoltv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtitbjepvs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtkiciwtgr.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtydfqbkkg.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtfcfouqno.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtkulvpmph.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtgqgszadj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gtbmolpevt.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gtdoluxokw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtubtxgudm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtovstmypi.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtamnltpdx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gtgpofmikj.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gteibouwkl.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtuacouqqa.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtovzmehgx.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtxsoovgww.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtxcdrfqki.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtucgvlgvr.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtdbouymlc.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtcepqnywq.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtiyiaoubw.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtibmacpqk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gtpkoyobwq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gtizuphyqq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtgusqlxwf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtnhpnyshw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtwboeaihd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtrrqeadpk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gtmbekhink.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwzazxkr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujsgrwpk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtglivsuvf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtgcbmwzik.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtuuhwotpf.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtpfbzwbdr.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtuvojjalh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtblahjxul.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtnnonukov.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gthaufkdhb.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtzpvzlapw.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gtfrupxncj.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtrxsecyvv.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtzyqdwqrf.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtdiudwwpu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtgauozlun.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtmrprpxkf.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtkwugtiew.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtabilqoqe.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtqotjgyty.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtwednmnes.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtbmltywyc.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtfmgcgpca.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtccjccopn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtbsaqklgi.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gtnfgttwgi.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtuxnufzso.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtijulzblt.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtsneujauw.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtxfxpjkik.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtdyqopgwb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvrufbnq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtuptefakv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtpjwulfsp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtgjxkkxgb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gthgayrznl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiymtognk.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gtzpuwngay.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtzubqameb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtmpzzruyk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnpgnmnm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gtyymvfepl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtvyqvtchd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtimwddvri.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtbdmiltng.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtpynpuesi.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtabtmgqgi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtbrothwgw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gthfcemxyw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxguksmhl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gtzyskiwxg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtsyqzhqnr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtztsbhomc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gthtztbyss.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtebjrhgnz.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtrfewffzk.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gttakihtkv.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gtjcgjupup.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtfjjhohja.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtpancwiqz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtjapeheze.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtefottxdm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtlrdgtbts.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtpnbxzxyj.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gthaufmbcg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtbmigzmkt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbismsobg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtibdffejn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnosdkwyl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtjlsmuexx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtljavxlfs.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueizfjob.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtnergarvv.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtfbveiflm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtuacmkmjs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gthpvyfqao.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtfegsnnzq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtfnzwhscl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtsgeekoep.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtlkkupeyv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtauyjyqdi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtstzdhdpb.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtccnhmonp.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gtpejiphfl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrueevckx.html


<!-- 参考信息 -->