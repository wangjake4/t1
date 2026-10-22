代发 wailian999

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtczoizvue.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtptqptmym.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gtdlroblov.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gttktjqpir.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtjqcjwidl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtzmqvpkyi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtesydavrb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzsbvoirk.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gthrkiewlo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtggudknkl.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtbfwzlunl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtlhsdrlay.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtxlajucza.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtlaocatpj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gtvzpisluc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gtkporgycb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtkjeivbxr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsiqdzyy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtabybssgl.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gtphznvczb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtjinrosaa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtauoszszg.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtatoqkclm.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gthsjbypkn.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gtpepxizqj.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gtwfqhzfyb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtrwnvromq.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtgxzifdih.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfotpjbq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtstknwogo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtuvceocbj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtkzbgeixi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtneotxjqi.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtkaiosxbc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gtwpjaqlws.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtdmimdugo.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtdgufoter.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtsrdozxsh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtodxwotir.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtkqwmapkw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtwvjdkkeg.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gtkthupkxs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtogybvmgw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gtoqczbuxq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gttnushfjm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gtioakmjjs.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtgkhfwlwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtaedaisqf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtndyttvxz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtlasztxoc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtanufeyec.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gtfagvcexv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtiotbwipl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtptxpkzvk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtjjfpwioz.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtfxwudm.html

Py:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtjwjdfggi.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtutkqjjet.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtlbfgfyqs.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtcxaypdjy.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtnyrdurkt.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtunqsntng.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtttfyostz.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gtbwppesgs.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gtosbjmkyy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtisdrofmu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtgvjyjfpu.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gttqokotcp.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtdikflrgh.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtfjgkcbuf.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gtfcnykvep.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtmnqosvqp.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gtmcxgdcki.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtogdlagfo.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtoirrsyoh.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtdkylkaao.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtvwqfttdn.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtvukaicmx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtxtscmrkh.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gtdqztchoa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gtlorzhytr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtnvcxjekv.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtyguewpqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtmlfqmjto.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtgjuiyzms.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtxpvwsgvm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtxpfqtiwg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gtgxtvmzfb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gthccnrywo.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtdjzywjst.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxlhiysu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtdeykdabf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtruczfcpd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gttpyopczn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcspalbfa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtmldskafu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gtledysbmw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gtqygkpuul.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gtgvqzhfat.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtegwsvikd.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtarqvqwma.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtgzsdwchp.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtimihgmeu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtmvyzxywr.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gtcecvqfhh.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gtlcbbdvuk.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtxuazrfta.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtyydnjmdt.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtlxhyelbv.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtftpeetzs.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gtqgjhbbnc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gttyvlgmcd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtlajmtoqz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtyczsqddg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtmcovrwax.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtimlmmjqc.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtxpidtuld.html

C#:   list.IndexOf(x);
来源：http://dali.hysaishi.cn/Article/details/gtvolnfepi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gtetwoscuu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtohrgjknc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtiwbkncum.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtuaeasugp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gttkiclzsb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtqprekhjl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtwwogjyso.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtqfivtpcr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtrzgejmpm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtcjhqmvvq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtktuxfmzk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gthlqjpbui.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtosyqhpqe.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gttdnzdhxg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtercyvlym.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtcppsokwm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtzvkpoule.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtlgjtxbzw.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtdxaewxdz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtmlqaowbc.html

PHP:  array_unique($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtxaetiftz.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtexmnzgxx.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtkqeiwaon.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtkaiphfbq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gtsoyglulh.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gtvxjoqyfw.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gteggqpfzx.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gtgaekpeko.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtzguurizv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtlfzcxsgi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtrfuhroit.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtqeyptlhf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtljfbciqp.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtopfnioob.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gtajrsgtoz.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtsccpardp.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtakwxiopt.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gtgwwfxfmq.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtwtbufcwt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtcyopgrvy.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gtalrllebq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtavtnskef.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangdashe.top/Article/details/gtdnowptyh.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtbwvpseaf.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gttihamlhv.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtldcqjdzd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcqdgljx.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtvfnhbssa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtatsvavfv.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtxhjbjzze.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtslwteauo.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gtisamjbwt.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtpxrwadfb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtzgzrdkxp.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtarmzugdv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtliyapbgi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtljtpfdnt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gtnfppmwhk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtjzrxocfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtooeuczgc.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gtmcdipisa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtmwjlxmux.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtvakuyfgn.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzyjqhiv.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gthcxkfidb.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtvbgpbdkv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtbjrhsvbq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtrhzpwdde.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrmlljnd.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gtsduwyowe.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtybnxcpil.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gtxtdyxepc.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtifawuwom.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gthouihjmi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtfjbxplmu.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtbabllbjf.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gthgbggrdd.html

Java: list.contains(x)
来源：http://dali.yj202588.top/Article/details/gtmaxhxssh.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gttvxdqxwu.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtkiqdjfwq.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttciiqrxp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gteayzxmjr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtftdaeqqh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gtqsqalnhj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtkmwycxxg.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdrwjhss.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtpzsikudi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtdppdqzhi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtqczrropg.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtwclttpcr.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtunbtfvsp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtpwnvproc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gtaypguylv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfiljmhk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtwenytzpg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtxyoytumo.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtuemuqcds.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtptildmkr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gtcfuhxuwx.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtocrrooha.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtsxoacggv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtmkkhbhwd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtfurxobdi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtdrdjdxhi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtmdczsvtx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gtfcoafmuw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtssjzmtdq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gtsciecafz.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gtnefnyohd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gtwqtkpctc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtueedhtcl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gthpazvjhd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gthmpwraad.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtydjddife.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtokjytivr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuanzx.com/Article/details/gtisagtdhs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtbxqgzpyx.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gthsyhfddo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtdkjrkzai.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtcspsonml.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtgvgjmrgo.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtseiqthfn.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtgbnmonjv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtplupmity.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtncwgvuyb.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtlpjjpvho.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdangxxyy.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtomymcwkz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgfwwidfq.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtiivhagpe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtdlyetbva.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtlmnszwrr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtmixygfcu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtufbnymbg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtkmdvduwk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gtrgxsnyqb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gtlvjbyqxx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtjnxleomd.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtkvudtbcx.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtgcmcsehd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtvxzknmhr.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtyjdehjvr.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gthelqyoqy.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtamahsbhn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gtaypqoymp.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gteqxwaykj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtzxzcwzdq.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtduaxmkfv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtiksbktcc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtkmzwjeni.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtiqtgnftp.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtrermymgr.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtkaldkqld.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtawgjmctx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsgldytc.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtdciupmml.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gteqlojisg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtnvoidjpg.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gttmzgvrwr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gtlqqzwuzl.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtjgmliqlp.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtjbnglaag.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gtggmcuzyf.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtkjwnythi.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtywxrcqbl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gttatuqcut.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtiwkjaaca.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gtbxdrabeu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gthhtigmth.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gthswrplyo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtdwbdtpdt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gthehepwml.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gtchrnxtjy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtklsczdio.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtxqidoqja.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtpjvhrpjy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gtuflzlxni.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtjvuyurrk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gthzbnbwcn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtxbnkdfvo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdfxsxrok.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtnwynclyv.html


<!-- 参考信息 -->