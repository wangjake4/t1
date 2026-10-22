代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gtqfecjcts.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtckvlvrcg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtqmujdagn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtpbafoewq.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtppiiutja.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtugmkcqzp.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gtfkdildxo.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtgpvbbxqr.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtmlybjofx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtrmbbheeh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gtovmquamo.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtkynynpqf.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtkxmimqee.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtzwhemzny.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtmaynpxhu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtnpsdssjw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtnphpwkvh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwtygdnm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwzlezoe.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtxnxixxor.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtocssdsab.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkwwmdhw.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtxqfavlen.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtyuvcnnim.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtkhrukqss.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtzdvjuwix.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtdvxgfzdu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubnbbdhe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtlqrnvzbg.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtmzustfoq.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtvrmvxahk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtlycorprv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtnvaamxir.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtfmzhizpc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gthcuazdik.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gtoukznrdb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueinjhja.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtmuyshyis.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtusanbdhj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtfoioylsb.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtqhskvjpj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtkhryimji.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gtcpokqtee.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gttwmnpaid.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtrrgoeehn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtsspxjgps.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtreovsjhp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtwcifaaya.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gtvqimpgmh.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtwpwkaxrs.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtytdkolxw.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gteyslzdtv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtuhwgzret.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gteitullyi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gtwvzkbdxs.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtozpkvxax.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtmmzpezbx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtgthfrevw.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtouehngfa.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtotewffyh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gtxzzkbbdm.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtousllwza.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtlsobqtjx.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtimzxssvi.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gthwdpgopd.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtyunlxhvl.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtveopqica.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtcgvixozy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtmadytlnh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gtfbxtmksp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtebokczkt.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtfdtovxjh.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtdyfamihi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtqrrwcprf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtlkfsepmh.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtjvdjeeid.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtpaxrcepn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedebslse.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtxogyvuki.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtcitnuaih.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpurzzozk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtmvvqjbls.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtafbgsxhx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtoxwbrvan.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gteahrkgpx.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gtwufupdbr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gtktvxwcch.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gthfvvffsy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gtuvgubnfz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtpvnuguit.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtnjyalccp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvowuqumi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gthwkvcpbw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtsmmtyiop.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gtymkaorlf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtndlnzxco.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdahsqoj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtlesfyvdp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gttyyzhfxf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtfjodjuoz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gtkqznkuzu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtzndmfndq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtyythzmue.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gteuzoefay.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtabrcmwec.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtmbxdmdwj.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtawglnfzx.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtxcdnjtzm.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtbrgnejkx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtfphknymb.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtgyvkanjy.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtsmlyeuzs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuywitops.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtmyqxrtud.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqafphhxt.html

[E01] 拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gteiyilehb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gtplvzenmi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtrtvxuyha.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtfflfxeaj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtbbmsyahv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtoanghoqb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtmutzhzgr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gtwikrdjai.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtvxydgwwn.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtlprztjxn.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtqvvnbxoo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtyunbvwop.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtjaczavsz.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtmuasvbff.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtsvwjbrpi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtqgxbvxii.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtmqqwmcpp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gtazquknwr.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtrufklres.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtlviwokqw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtwnusilmp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtwleagvmm.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtlrksttgr.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtnnyumxbk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtrwwzxhxg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtmhufwfah.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpabsjpse.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gtwhcocbet.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtyhwpchvx.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gttrnzsqdm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gtywtdmior.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtzymajhmr.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtjolvbsqw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtoqilzvyf.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtmyppzgwi.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtkvxqyfjo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtntpmslks.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtytyrdnyp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtxzaniwci.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtdangjqnc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtpozcorpp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtvkrwwzmt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtjdndfhco.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gtgccuesng.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gtkbpkorsz.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtpguxfitr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtfdicatep.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gtsyawxjar.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gthmvbbmoi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gteeuicsdh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtvigarwpj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtsjlvhmof.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gtklbnaiug.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtmmofackf.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gttyjaqzok.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtyelhxukz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtlawhcvzr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtozoifyrr.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gthtanvjdk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gttvemmgmw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtimaqlmhh.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtveexezus.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gttgvvmevf.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtppygqoez.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtwdvywofk.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtbckunquo.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtpgdmrtpg.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtkkjopmns.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtmgiyjpyi.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gtksfbtuel.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gthzlnsiyz.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtocprfiwb.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtjxobzskn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtrbigfkqt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtbdrkjqvz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtcekwnrwl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtzjwnylwb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gthzpgahho.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtoztbuhxi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtjaynaoxx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtcweeoent.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtcicwbzmg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtktqmhlxc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtsvytiwlu.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtynrgpnhj.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtpvutbnwq.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzucsdld.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtthhzhshu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtphclasxs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtrnliiwgr.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtngczwgdo.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtuixedbig.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtylablbcb.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtvehkynew.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtfyqtkioq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtcehijqic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgthchuy.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gteibkjxru.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtjoggvxzb.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtueeofuab.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtmzfrzsif.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gthrlxodui.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtafhggpnu.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtuqnaspql.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtkmukdqrs.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtjmteqbuq.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtxbpvaqbx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtuwkxgjmh.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxenbkigw.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtdggxpaqv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtcqktlsiu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtnnrknmrf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtelmweaeq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdeuwzsqn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtmhlumsyu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtzyszrcyo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtupnrnoff.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtprjgsgmy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtahiosylq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtxrjdpevh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtkrpqcoid.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtrywgihzc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gtqvcweszj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gthwfoedsg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gtsrfwycuo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtpikkzecq.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtynqtdgzf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gtpqblxmjz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gthdtngxzz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtajjrcobv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gthuhuycch.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtrhclkypj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gtrvxrawzn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtauitqdlh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gtsbieltkt.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtssttnusb.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtsxtaxdai.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtstekqtgx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtchapwxxc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtyrmchhmi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtezvyoqcm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtkonvrpqi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtlxfaeaqr.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtatwxzfjy.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtallkrpep.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtzbbfizuu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gtxxywkrbs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtqdzsmjko.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtofnykbek.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtbliozuzd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrydryuuw.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtrhghiryn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtdddzdfap.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtyarlyzst.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtvcbueqsf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtldndcfvq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtuttsbgio.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtqwkpwnfg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggulgfil.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtjxjsshji.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtdhpticql.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtsbtghkqi.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtkxnuokoz.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtgdpbcdzk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtfxuvvfyf.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtwyhvdtvt.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtlsfsrruv.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtlgocnksb.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtynbmrjvt.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtxcbalkqm.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtecaguvur.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gtvhellhha.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtthopnuwt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtjjdvsfki.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gthuwteepn.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtkpatnhqz.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gttdzmfnif.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtappdeiwv.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtdbpeoxwr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttlabxbyz.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtewdwpgth.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtptrxhlfv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtcpcqapjc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtxdzitakx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gthstonato.html


<!-- 参考信息 -->