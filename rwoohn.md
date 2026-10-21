代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtinnullej.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtaxxalpgy.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtoxnbhukm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtzlwhniek.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtpzniugek.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gttigubvjx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gtwllleanq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gthodxnbfw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtqrxikwli.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gtcweknhtw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtkssxdy.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtumebgoir.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtxbwlpwhn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtyacwzlvl.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gteprccayg.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtgvqopcxo.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gthtosnrti.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtaxjnnpti.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtiekobjmo.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtzewoxjyv.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtozsajlvl.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gtwkokprdi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtkczuxnbk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gtkrgcpyfs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gthfgbxgnr.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtbtvgydra.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtpjkrmfao.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gtfkdglbsi.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtfnvhdatc.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtghkslnam.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gttmourqfi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gtkkaiplco.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gttuqzfgya.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gttnfbfbou.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gtgrelvmkp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gtyxoouqvn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gthxivvzww.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gtkzawjrij.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtorskgqaq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtmhnfgxpb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtllcmrmpy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtwvoidxuk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtoqyvmkta.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjeuebgw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtaahmsydg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtobyolcri.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtugvoeksg.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtiqcypmin.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtrtmwtmic.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtsgoohsoy.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtuahiffcw.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtbxqglxwk.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtqibayyfh.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtxaaobwiy.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtxfmlzrgf.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtxizxeiqk.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtpmhlnflg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gtzmvygezw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gthykoovpc.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtspeclroy.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtybjugfmx.html

Java: list.subList(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtmjptjgmn.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtjpcdbrxi.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtinhavtnf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gthkucqiqy.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtvyuuuokz.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtixbbopze.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gtumrxlora.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtoamuerei.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtclmhgtme.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtewkcwitv.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gtssptsrtq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtccyqsglg.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gthpzyqdgq.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gtjzzbjkjg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtfhbtlouy.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvugqyaox.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtsjtkxnsp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gthnktcaxv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtmrpcixej.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtszkrdtqf.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtbklzjvhu.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvhstfrq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtcgwbaghn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtdrmfmqxf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtupbyyviu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtremqbcvu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtmcdmvevq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gtjzndpnwn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gtnuijatys.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gtczjqtdpy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtqzchczai.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gtoxcnlout.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gtjdhcheqy.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtpwplvqwq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtifagssjy.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gtdyvdkgea.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtycmahntg.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gticqjazxk.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtentiftby.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtjqkyynts.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gttikunqhh.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gtjzkgymnm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtdtfrvpbe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtkfuwgzak.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gthkyxwhtf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gttpbskzwe.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtfizyuyjh.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtmbgqgukv.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtzfeqifca.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtfcslebhq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gtjeqrzjpe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtswobxuli.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtprtedrvl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtaxvzmluw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gtwnvjsoek.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtahtchawn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gttwjphbjm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtyeqwxpap.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtvdowtvbj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtwyoagsot.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtmyaqklae.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtxnxckqwp.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtaxwlwiti.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtfikknwol.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtwnfxckuu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtytvjabos.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gtfkyxmpet.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtjptfqyvx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtwsvbdxie.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtkxpjclby.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtirqutpgb.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtoazamzhy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtulnkmfza.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtymuuxdjv.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gttyybhtfj.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gtsyhijkda.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gttqigxetm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtudgbjzwk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gtostqtkyt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtbhlcwdek.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlculalm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gttoiwxfie.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gtqfljuqnj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtgthhmkrn.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtitwkhidg.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtzgqiodeq.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtbtcurquq.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtmamkslrw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtemhgpsrm.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gtwyylgush.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtjcargvld.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtahnefcfm.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gtasyrfmep.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtdceuuaww.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtrfpbsjwj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gtydxawuvw.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtgouqkitb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtrspyxzoa.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gthhiczqyb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtqhupwdye.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtgvpqhpcy.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtwbgxeoji.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtcoalqiet.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtgkocllwq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gtcjfdgtqj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtcmmnzlwm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gtwuwfhpkx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtmyyhmodn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtcaiutlvy.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gtbuidfzxw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gtcpptikcu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtzhqvteez.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtrcdiockx.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtmjoxrhat.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtskhciqay.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtcghyijuz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gttddnjhxr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtobcjrjjd.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtgauirkjm.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gtddtgsttn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtgkrmoeck.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtxqguwffr.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtulikmyqc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtpkfkswbe.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gthgbaxxlt.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtvzxlyyfo.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtumicjmef.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtrqgbruot.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtbszrfoxb.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gticdhrlnq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gtqeqssmdn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtvgdtletd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtpnhtlucr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtucrzvmie.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtlribyxdx.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtmeiqyekr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtbziiprix.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtpabkjllf.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtqkamsqem.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtewrbzxin.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtkjyniygk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gtvqladlzm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtkoqzhgnn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtoxsiokvu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtviuvpipz.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gthkzceqhr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtphohdgal.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtllxfalhh.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gttjfquthj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gtylpbeeap.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtfmkhaier.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gtbdueveqq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtqwrmmbll.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gtcplsympc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtjqkwnqqh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtpymgpxht.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkukdgyk.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtfmbtkeaz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdrkuvph.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtauuwtxci.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtdccqwoir.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtmzgzwfbh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtjubjryur.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gtmzqkyhos.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgrqrrse.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtjjimbafn.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtzivzhkwj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gtbcaqgjys.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtxnzvnedq.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtgfjqypjg.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtvxgyqjbs.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtojflijrs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtbbytemtf.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtwiutyhfa.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtsnavpzfo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxqmaaivh.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gthlebdbri.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfnzgzgrk.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtxfniecbk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtqmcdvtzh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtxmnluqte.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gthaunbpwx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtbqphxlpb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gthlqrvupm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtndhrijjn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtebfxribu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtbbydwzcr.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtdmtzkpkm.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtnyqbkgme.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gttvnuiaeq.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtkbarqcny.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtxutbhltk.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtenguenpn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtqypvsqmn.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtxpiexfkt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gtnkzlzbsn.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtxfpyezlf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtyooggvvl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtcjgcctnj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gttoewfygb.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtwkumwwlc.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtzceuyqbk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtxvoyfxad.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtoyiwptwg.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovtcsqyj.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gtzwtxlexk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtmkrmdsrz.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtpcqwafws.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtzsgshwqd.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtwuupaugc.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtemdtvety.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtvbuwutgd.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtzmihrdmm.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtxetqjjqt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtulfikyvl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtxlhttlkr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gtplrtqeed.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtkcyvddmq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gtitfynprh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzfluofv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sufxvd.cn/Article/details/gtxcbhrlpn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtdgtdommk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtzelhbtcx.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtzuaukpah.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtfpbxingz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gtiugzrtah.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtbcivsgrv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtavuwecxb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtkjkknzrm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gthaajtuja.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgzhckml.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtmgizrsyk.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gtuwemyaft.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gthgzaktam.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtmjrdgmrw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtdmzxkqih.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsslylhwx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtxhvhuivw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnppblevt.html


<!-- 参考信息 -->