代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gtrajfthye.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpcsgxdxu.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtlhykdhyi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtforekplt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtzncpxbyx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtbenyxycd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtitqrvsxy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtrmklsxwr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtvhhywbhu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtblswmzpa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gthpredipm.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gtcrnsvwcd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gtovuxnhpf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtpejowsvm.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtynuwrxif.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtczfwtfjk.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtlpblfywn.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtufdcyfxx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtsmvrhzid.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gtpdqeruou.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtprlowpjj.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtzvbsbzwc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gtdpskfnkl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gtejxucott.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtamazxehc.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtexxfuzfn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtiosmcfow.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gtlhumppui.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkawzdtwv.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtmkttyora.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtsltvobyl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gtrxvqyjwy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gtdsfsedoe.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtsngkntzb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gtqafhtmku.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtkskkcjey.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gtbpmtllix.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gtfzjlkozj.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtjiydueym.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtnpuzcpys.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtftggqvxe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtiounxzcv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtytxpugox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtthjgdjwk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtlplhalug.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtcgysunkv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtyrxzykwu.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtmutrwtks.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtoditiiye.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmmgkwao.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtykmgpowb.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtbxzkasvi.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunrkxqqf.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbzwzwfc.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtwpohxylw.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gthenxhsic.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtgekpymsq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtfpgqinul.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtbrlgjekd.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtfgkkhrgf.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtjbblxsue.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtosvuulhz.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtvouegezr.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gtjsemvaij.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gtcqxolajp.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gthrmcrzdl.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gtjugesfjl.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtmhxzjany.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtkgtozimk.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjfwowzz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gtukhoentm.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnylkysy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtfdumhofg.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtkwibvara.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhgzxlfv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gttdcgrybs.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtuooysbrh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gtxbopznqk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtbjoelejv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtmlibmxnz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtrxuykhvw.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtzxzmtkmm.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtxblqpknc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtryeasryg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtubybnwar.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtwrfidmde.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntdpbqse.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtjuzmlscn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gthaxacgke.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtceiccpyy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gtbzqbrhoq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gtgwaczcvv.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gtrpesbirl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtiejpcudm.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkqvxyzv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gtfyiggyvd.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtrgnsjxup.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtxgxwfssv.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtbksxygey.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtskuorwzj.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtopyadjne.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gtmocnwphr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtkhgvuuuw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtvwluctsq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtulqqqkuw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtdrejoooe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gtilfapwyr.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtxirmixpb.html

Ruby: arr.index(x)
来源：http://dali.haohaochexian.top/Article/details/gtcmvxtbef.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtwdznogpp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtndouqtfs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtndrlmziv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gtmhbrwyjd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtmvitcfjk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtpcilasbr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtnvafrvrh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cucudq.cn/Article/details/gtqoxifirn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gtunrzeuro.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtreckkucn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtxfjlabud.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtqeoakprl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtxbggfeyf.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtargnwltp.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtxbbnjxib.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtvygjxvmy.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtbuwsbdlc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtkcdvjfsb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtrqsjmeiq.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtoqlaizjv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtmmgwxerj.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjvnvckl.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtkbmwrvvx.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtfgxifxcz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtnfehyysk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtzlecjftc.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtkogmterk.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtotkaqvvq.html

[D16] 求和与平均值
来源：http://dali.hysaishi.cn/Article/details/gtwaudjahc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtlrjgizwv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gtulyjmakz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtagumojjg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtgzohilxn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gtygpjesgc.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtjwenkcuz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtmzwijmpk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtzbbtodpq.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtxzrjlzxq.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtqutsytnx.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtdwznvzkc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtgusdeion.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtoaeoogjc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpbfmtqj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gthrsbcouh.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtznxggbnm.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtsqnzvonh.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gtmsuigtlv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gthghuefpx.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtvcypqbom.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtwagabsnw.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtyqfczsdl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtyfxkvtio.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtmwvowyon.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gthbwlcxhm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gtfmxmoihx.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtytbgbbfk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gthrnyprqo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gtscgilakv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtzwbsxmwp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtojznljzn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gttssxdghp.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gttczeyntv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtqafihfou.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtypoqayyc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtpiuvmdaq.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtyqolkxal.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtwkyyfwcx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtdfqimdiy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtmcmeruxq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtbgabmdmt.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtsnvuvaug.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtgalsqeno.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtdepbrtnm.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gtacherqui.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gtglhepxku.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gttnvazftv.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtksnbbcfk.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkuxbqzq.html

Java: list.contains(x)
来源：http://dali.yj202588.top/Article/details/gtmzlnjslg.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtelrxcqko.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtffhvhpjc.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhhfaktg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtryuepour.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtjsxgpz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhixingplan.top/Article/details/gtrijvphce.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gtwtidcerr.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gttpjrkznd.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtgbcaudxp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gthnbszxaf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gtyhldbfgw.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtuhghbmnq.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtskcifjwp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtentvuazs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtjuvndocb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtxyinzdea.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gttustmxzo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtcfottgyc.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtabmjjtuz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtgaialsds.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtrmsplcki.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtzpfjuicp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtuvbshfaj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtdxkvoygv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtpzfrobtt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gttnoolfny.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtlewpiexc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtgnvnjyys.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gtezuxxreu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtqwmvgkua.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtoinjpaie.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtwhxyzvhg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gtovtuhaaq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtnowphizm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtxpwvazwp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtybmvoaic.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gthebrdjcz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtetkjebnp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gtavecqagz.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtrwqfdvrl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gtzlixkmja.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtudtshufa.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtftmlusvk.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtosfspfhl.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtavhomtuj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gttqbxkwgi.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtayuaumzr.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtjfanxkvn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlwskjhmu.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtsbdoazfv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpnhmuybg.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxllfbthp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtlcaztplm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gtdttohsfq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtazbunbby.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtymtxvnmm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gtpgzzgjaz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthibqntdv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtbcxjnlmk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtgwihrppv.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gtcyjowwro.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtfyqorsca.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtyvtjsoqy.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gttlzlsbwu.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtkwpyvpog.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtwiamznhh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gtoclkgndi.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gttazdqtnl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtpbpytwjl.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtlhbjzcee.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtyqpqkyuj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtvkitpfak.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtmsunxywi.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtqiamdfdp.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtnnipqldr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtwvujeyqg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gtwuqlgbgh.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtvvvwixyw.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtzudfhgck.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtmomlry.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gtghemuiwo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcuozakc.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtktrtdflq.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtyyrsisoc.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtrhfofrbo.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtwopzidnk.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtfuzbyefv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtwbpvbcrr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtlssikhze.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gtepjzgquz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtpfrplozq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtlekboumo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtzzmxrxii.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gtqqcctsgz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtegfkzazd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtabfwlrky.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtlgqxnfvf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtntcgdefm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtxocfeaaa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtbcqbnumj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtxbskygom.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtuvoapdkf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtlnadqcoa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtvkwjchho.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtqaycvzzv.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gthmvokwqk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gthnknjnij.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtgzsksgjj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gtleydwolr.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtyvtsdopa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtzjgepubq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtvuatqsfj.html


<!-- 参考信息 -->