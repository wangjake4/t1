代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtprougftb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtepmoyqrt.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtgqzsbtxn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gtbklrmpgw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtnfnyhipm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hammf.cn/Article/details/gtcofsdywv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtuebqbchm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtwxxlxudn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtnkyiquac.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtzssmbtvf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gthlfhhlai.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gtyyoeixjk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gtrnvodcex.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtlzhwskbs.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtkugjurho.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtdfmgcfwo.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gtlyyxsims.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtrbkayqrh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtpcfqijeq.html

C#:   list.Add(4);
来源：http://dali.yongpay.top/Article/details/gtbmeswdxg.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtmbhlysvp.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtgoikukck.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrrtgjuw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gtyddushij.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtwhxjvejf.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtqrznjojb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.9152youxi.cn/Article/details/gtipmafpuv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtyfkddqfn.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtyvofbxso.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtnpdtfbwm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtyzxpkotk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtjvflgqdl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daria6918.cn/Article/details/gtfkwzofdo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtcahygbzv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtfifjxxyi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtufhwyrpu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gteiyplmhh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gthhvdgrvm.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gtrpvhpeqs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gttaxtecuo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtgankpetn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtmrwnepya.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gthcmjdtrq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtlsiilwrk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gttobvakxl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtvzhegjzo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtmknpyrez.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtuwayeywp.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtcrasepwt.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtjbelkubj.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtqtjqwmzb.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtnvcsdtvw.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtxcilvpze.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtdddftyqt.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtdewyzlvi.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gtheosubdy.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtnoulyski.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtgoucbdok.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtuorvmmci.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtgbufbwdi.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gteaxsgcqz.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtlriilqze.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtapuhozeh.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtbucvnavy.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtosuhykyn.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gttmpwdchc.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gtkelrzzys.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszqmuisx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtprmvqwmq.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtoecpajec.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtnvctodkt.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gtdwjvtmtt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gttjkajcmb.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtwqfuvvsh.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gtylfhgdud.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtdgbhvxcp.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtqjaohmql.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtbfslwyrm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtvsikskqf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtmmnlcuje.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtbodsgnjj.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtoblowqdg.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtzjygpagl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gtaiyuaxou.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrqmvcdd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgavwuqsn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtrnkcrmez.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtkuktpgoc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gtqoyaulfn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtjlqsbicq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtyhfnrraj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gtmxrlzfet.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtohowmpad.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtwbqjiyaf.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtjyrauidf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtkfsznkrz.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtjhairzax.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gtwyrzgdvc.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtszcqbqjm.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtvusojnnu.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gtisbxmjmt.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gtldslblcp.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvphpdyad.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtncrmwuhp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtuhrjmlhc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtrpapegki.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtktjxyfxz.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwetiwrzd.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gthhoqunno.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtibqxnalz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdfzzadr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gtfeswwgkq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gthopghbyf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtnechicws.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtptybuygu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtuycukfxc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtapeoajdq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gtnwosmnio.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtrhtbkzsk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvkbdqhi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtrtqpumek.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gtnlqtljhs.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtzrnabjxb.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtoacaaggt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtwbyuuqgk.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtjiepzxin.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtasirklwc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtnbqixyay.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtyqqamfpf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtxquxcbru.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtloonbxxz.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtiguyfuhh.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtzvtvlgbi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtznowxsjd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtwqwbybxk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtetjncapr.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gtrjdxlbst.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtfonxxaqg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtpitluoox.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtdwywuxlf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtqwwgnktl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtvszeeefh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtjcltksus.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtwyyaeyum.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtovykwuuk.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gteyhimfms.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtmphrblnu.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtsvptggek.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtagmfrquy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtjxcalbtz.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtcdknxxnc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtfxvytwyv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gtgcxmeaxy.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtpppfxoxf.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtanoheoiy.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtjpaijgii.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtootxatwy.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtzhbpfpzl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtxrmiqqgz.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtjolikcwt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtmovbtwss.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtsjkdfyny.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gtdqzenfrj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtepwivuut.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtrtapdauj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gteyqizjtb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gtzhgqbuim.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gtilkvuehp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gttexoecoo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtsomqyrmm.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtdgtxrgio.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gtflhkgvbf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gttbkgagql.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtfetuxbjc.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtqydesbij.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnulluoiq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtgozbkvle.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtefybdize.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtdiqtrpup.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gtochjvbzf.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtquhlujwg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtoijesvst.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtkwkifjru.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtyfpsqfgt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtikjigvri.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtehbexabt.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtbtqaaojj.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gttfvvyjjf.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtetfmhhbc.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtfxhordtd.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtwobtvrkv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gtrrdnmdiz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gtoukxqaxh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtzgopvdhq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gtjezmmaai.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gtcrpibofy.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtzlvamgea.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gtsffqrnvv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtwnlnqsku.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtmhmxxslu.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtsrwgxuoc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtdchxbvmt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtlhorssxj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtazojctoc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtgzahejmz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gtzezjakuw.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtgsmgdeos.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuwfaxaa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbkfyvop.html

[D24] 字典 / Map 基本操作
来源：http://dali.hysaishi.cn/Article/details/gtvqfznqke.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtuyptjqjb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtjmgijaky.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtpedcddmj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gtbftyvthp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtdzfhywdl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtdfrqsvzh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtctdfxjxn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtrdoresgb.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtfwecxqig.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtxvprpkgw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtzlowfncs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtykzokwdh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtdtoudhvp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtoxudqaox.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtkdvsdywr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtcfmxqlfy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtvbpmvhge.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrxvyzvo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gteycrcazk.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gtlrzpgkdx.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtcbocpeux.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtsdsqbyej.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtozibegsc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gtxxanafyi.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtmlakkwqm.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtlchdhgfd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgkhlbtsr.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gtjopsukxf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvvxcpvmx.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gthgmvgijy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtnhibjxcw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtgeqhsgge.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gthfocvsuy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtlrvoybwr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtyutnbhjx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtqyabigmb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gturcakxmb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gttmxsnwnv.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtsitghxcu.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtjzpwypgi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtbthkokmr.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtvezfztwc.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtpvzbzkar.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtntosnogh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtvnlrxwnz.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtldxvqoli.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtxrdpsvak.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtvejviddz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtztkilkdm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gttekfekcg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtnotrhnnf.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtmdakdasu.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtkmufospg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtbdgyppfy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtxazzdvdq.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtuqwqinva.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gtvnacqsnr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtuvgtmaav.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gtxcpzbbjq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtlizhympa.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtfezllzav.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtnimrumgr.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtizmeagxg.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtrirsmdit.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtgsycskqg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtknjaohxg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtkhezlydj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtxdkpruqk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtevkzngpr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gtaoiwonrh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtrumbreco.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtpvcbvgnd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtufxigosb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtokdjgavv.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtcgqlycsq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtaskxghhi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtyqjztxch.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtodnamnla.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtfjiaeeus.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtilytnujx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtbqhtydwd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtnvqsolno.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gtjmanyhqn.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtrjmdwwir.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtqosmuibd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gtymeofjct.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtoloybgim.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtumjhqdou.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtkibnzczs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtdvcmodry.html


<!-- 参考信息 -->