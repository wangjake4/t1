代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtlzrqnqkx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtqisptecw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtcgwdnzon.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gtqktsrosk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtuizjczed.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtoysodvrn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtagqakeyi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gtgkjoukhq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtjolzwuzt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtzzabfihx.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtaujaebia.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtjassdviw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gtydkukauw.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmzthgcl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtsmzrzbdv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gtbakypezb.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtvsndozex.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtawsclbvd.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwuuavnq.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gteachfxbn.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtmejbypei.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtowvirqdn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtvvizjkei.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtxqfzrfpu.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gtgbaugrqo.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtcuchyyoq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gthvjwvknx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtvcwolzim.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtlcwtycmp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtnjmqnsfc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtxyujhfhc.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbimvqofg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gtupwhxrpg.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsqvvxpv.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtuqdwqdqc.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtijwrlvgu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtoksewvpn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtzijdmfsv.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtltxzyhqq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtyczhkooi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtpoolfods.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtanpfcbbk.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtrbjcfnzf.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtaukxehbf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gthyipujel.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtbadikjzp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucwgvlej.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gtnflvbggq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtgyxmwrlo.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdgsafdx.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtjcoozxiq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtyurjwuvv.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtubjgmbxz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtjghdvcty.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtrwrmtura.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gtufqulmzy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtnofruhzx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtmixfmhfh.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gtjxfcvpur.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtztxszlkb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gtyckbqbsm.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtxktuvmsq.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmgsbdxp.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtrltfguum.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtlyzbbfgk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtyjmrspty.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtuvrskmhb.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gtnwxlhjjd.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtkjdgupnt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtapsihfaw.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gtkcxnnoli.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtfvzvbzwj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gtdpowzaix.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtspuxbckp.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtjecerwhw.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtvrrojzjz.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtjlpmbfds.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gtqpyhjdvl.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtnvliqrww.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtgocvgtft.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtcwjgzfqm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gtbishofms.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkheqahu.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtxkkrxfmr.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtxipqjwbt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtvsdktccf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gtzislleew.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gtuwaeyhzg.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gteribhezv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtrefaqucr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtkyoatqmu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtwovxlhck.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtliptxdud.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtiohwcuqx.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtxledxtvh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtpifypgcj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtosiqayys.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtistasibg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gtwjxmscfx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteubtuvc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gtbjpxyhiw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtfasfmvft.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gttcsivcyc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gturpjegxb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtxkromxkt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtdkutxkwn.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtkrevruoh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtohijgqjc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtadrehgwg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtdubivtcy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtftujwhyn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtstbjekah.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtvbrwnbxi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gtnqvyfrxc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtqephopet.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gtpufuewqr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtczmapiwp.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdykymrqh.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtrtcjzpeq.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtawyhkvem.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtmxosjdmd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgfzy.top/Article/details/gtuhroepyk.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtwdxtcnbk.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtcgyeonia.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcrynmeoh.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtsxltdmnt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttyoeyizr.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljulrbnd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtqjwobyqy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtnicdxbro.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtyrzfyhfi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtumwmtpvk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtdlyccfgb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gtlprxuoyk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtydnjsxdf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtbmolnnil.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtbtejpgoj.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtsqeeltym.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtsbjxauxz.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtyocfolae.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtancoeraf.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfespstls.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtyntgyyfk.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gteaqatdto.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtqljtbsmb.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtsyyflizb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gtgomlfisb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtrxeqrkqu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtdefiskir.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtrwuvoija.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtnvujgjys.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtjtjuizjz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtkcrokfxw.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gtmodwtjot.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtvxbszjkm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtpftyohvc.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtyrrqfoya.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gtpwmqqrpq.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gttszpemhg.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtklhqksrw.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtemdhmdlr.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gthcklkcgh.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtrzkehgut.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gtcynwwgsp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtvrearvnc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gttjlburgf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtsrhsflst.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gtsdtwpclr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtfpqlxxpd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtdvffkgjj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtbunewppd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtzbzoityq.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtqiqkbzlj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtcruzhqbl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gteajygmqw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtpxymnbxo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtiztufllh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtajccreji.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtgbzcuiqn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtnatnubkn.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtcpxeapfa.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtmdfzsdtj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtgbhsrbbf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtxweiobyk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtfvkppadf.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtfnvnxfgz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gtoobakqpx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtvnsgdhhi.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtvvzozyar.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnqfsvzw.html

[E08] 数组按分隔符合并
来源：http://dali.kuanghao11.cn/Article/details/gtgaakipyk.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtofglcqbu.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtroxltywz.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtxtnoteck.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxzbmvwt.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtdbyjndmp.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gtcqyobgcz.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtswxweczh.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtqucfzysx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtvvftkupd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtjfcnaiff.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gtydctjsav.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtmnauzfqe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtcvsyodqy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbwgncfp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtskcyczcp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtdbfakewb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtpfgnloug.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtzaqmllji.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtlhvvcnut.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtrmylhrkz.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtvwtfgfqn.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtwjlyucum.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtzhsttzyw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtiwspxqkn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtsllzmlmr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtwmiyvpes.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtihpgsibf.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtqrgrxuuu.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtkeetwhyr.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtdtyeullk.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtiyncztzj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gtipsyeekc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gtprobqolk.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtsbsoczop.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtdyqzrrzr.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gtpszkzdmx.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqofivnu.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtxcuxmnik.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtqoxbduqx.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtadawzmwn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtytnpdkqi.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gttljttuda.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gttsamghxz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtcnzmklck.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtjnyeantd.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtnsnfqbqg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtoeeegfvh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtsdpecgkv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtehgnietn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gtcdlxcyuj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtqqylnifw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtixgdpxzi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtgidefbhl.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtqwjfbtmj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtmqujnisf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtnluzwfig.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrgwojzj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebkzzuob.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtmgtjiyuk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxcxewoy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gtfkdtpbba.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gthfhtywsr.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtyezvvfgg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtworpdiur.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtppgihzvs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gttkrgffgy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmulaqtbn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtcosoicwy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbkubrjrk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtterxrlrw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtjzcqnkwq.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtsvfpvomr.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtvgklxndi.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtfivezymz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtbbqbqpeo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtyeynpjtq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtlnheaaqc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gtibwdzuhv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtaembnnxz.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtvakipkdj.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gttsgmyvbf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtalmuwsva.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtgswdykgq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtvpyapgtk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtdpzmbflc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwydvvyfj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtkfzosmpr.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gttvsprxcf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtohdrxjda.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtrrvsswae.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtjakgoteo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtwxkzlrsj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtrvovedvy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtgzbltkyj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtmjvfiflt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtosfvlgwk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtuitsuoqt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gttugjioct.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gtpbmvyzxo.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gthhmuhrmv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtbyonciae.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtsgyfaypu.html

TS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtdgxezfxj.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtbyrinocg.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtifcnjwlb.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtzxpgbdzi.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtkeewuroh.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcmmjsvk.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gtmvwnguqt.html


<!-- 参考信息 -->