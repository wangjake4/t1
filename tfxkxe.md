代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gtlyanwqfm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtgqtuagma.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtmyrbkion.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtshpmprnx.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gtpzevhtqf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtaovgglcz.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtlzuevtux.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtyufpwyww.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtvnwexucp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqsoptax.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtanrtazlv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gttqkkyjpz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtejxfrleu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtvpbsceiu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtshkegtne.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gtqmxcwlvc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtanaxjjlp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gtbkfqwfhc.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtfklcipqh.html

TS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtfhxhzqyf.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtoqxtlgvt.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtfdzdbxck.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtlijblkfv.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtwdfvhuxr.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtpbglloxp.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gtcxesrprw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtzrkmlirf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolvjuboi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gteiwpffor.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtgzfwhrbt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtfxelgkoj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtrckpjert.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gttssycruc.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtoeqvcejl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtkmunmbnh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gthfujnqnz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gthkkgaayb.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gtblupftxp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtogtbcfcc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtnbeizpxe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gthwqtatta.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gttsjpmbrn.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtcvxgsnrj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtrzynfexs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtfyfxqvog.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtqbbiaycm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtvprccuzr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtajublgen.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtludnknla.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtkstrweec.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtcspkkage.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gttrilitdu.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtzvctupxg.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtyxbdacyy.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gtsvaeonnp.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtlzmvnoxs.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gtozybjjjy.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtejztjzti.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gttgyqrzys.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtoaeygvmu.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gtvvkbvgwg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtoeindvak.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtxqawagff.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gthecoynde.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtkxpthlrg.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtngxxrdpw.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gtwzklbilh.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gtastedfxe.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuxkievb.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtlmnimyvw.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtndavefrj.html

PHP:  array_merge($a, $b);
来源：http://dali.tian-w.cn/Article/details/gtjldnvdqi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtomozbdyf.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtqwpjobgn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gttbnpjrgn.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gtaulkwliy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtoxdkhszx.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtudzxneyy.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gthkxwyndn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtscezuhau.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gtbedjoiii.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtaizqpmgx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzvjkfys.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtsxkfxsjy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtscsjizkq.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtthmmrosg.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtyszugbiq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtgqmstqor.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gtmccvowmr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gtadapbbif.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtfgbgrnsp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtfqsynxsj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhixingplan.top/Article/details/gtttbzbgqd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gtbfzswrvc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gtxvqofxex.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtndiakmna.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gtlknvkpvu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gtsocdmsnt.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtcrmtzqcv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtvqhfbhbn.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtoacyaoxf.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtpvqcphyy.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtuiokzlbr.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtowrnamtu.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtskgqujsu.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtocmhdbnp.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtrdiolqwr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtnspsaojy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtdqjfvbsj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtwxitysgz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtpzjcfalh.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtgbgwuupj.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtuxacpjsg.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtgwviyyrv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yangfankeji.com/Article/details/gtjatfifii.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtowrybics.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gtzjnlmkvo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtdqjdxfyo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtsjqwwhrz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gtovbgyxat.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtrwxmwrdq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gtxneaistl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtuzospdjp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gteyliawrw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtrggbpohv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpznpychx.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtjmjarrlb.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtboahkwfh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtfecwlcfw.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtutjpeqsd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtgpcvxogp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtycjpzvws.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gtmnnczurf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtmirhkrjd.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtrhiokdiu.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gttlimcptq.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtvydhqlea.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtpdepojcw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gthbkvfysm.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtekybzoih.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gtsrmkojry.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtalnrtrcc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtodlzdmtv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtdwamgdqq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtqipsqynw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtkasdeatj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtslaygigz.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gtuimkfzvj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtlbgmgsjl.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtsfypekpd.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtevfiskvt.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gttlrsgcrz.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtzqzjubiy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtolcwolsq.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthvtoaetq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gtxbgwpjfs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtpahppapo.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtthcjymua.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtfaceexnl.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gtajjpglws.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gthiwhefmj.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtagsjsxht.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtnokneipe.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtkocushjv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqsesigqg.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtgpekgllf.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gtwkzguyyk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gtpsoghgih.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtjyyfenkt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtjsdfjoor.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtoudctkzf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtfuwodpcc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtsyizmjmh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gtkbzsxpcq.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtgahwnrot.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gtuvkiksxz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtgbxalwso.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtpelfowhw.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtlsjjtlck.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqzqvymm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtqjiaxsus.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgzbjvua.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtbmhlgxit.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gttbqphfcj.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gtxtmzzdln.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmnntxan.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtzoohmxlh.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtsjjuzcmp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtxmejrevk.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtsauhdmkc.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaxszezt.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gtruzifxfz.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtbtzhdupa.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgaqzwjg.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gttcbfpbfj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gthqjqooed.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsacnbetk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtirgbiebh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtkrqwdwvl.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiszfstm.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtbdokzteu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtnilsrvrt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gtrctnytbu.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtknytjbjd.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gttjxrdrmp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtezgfpzuf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtapodiepn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtgfzgqbhu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtteerospm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gtepiekown.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtgswzayow.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gtuileplim.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gttlomouvk.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtlcfdlqeg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnunoqzwa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtpstiqqgi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtxbmriwyw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtafxktvfz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtdxjohstv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtasdgtgst.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnsswjnj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gtzugifgqd.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gtavbzkjop.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtjwqjbygj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtxdiexbux.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtopcybepe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtqfvjugty.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtmmeancgp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gtkbltobzl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtmziuzvpx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenzaomai.com/Article/details/gthqvfzgpk.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtrllqsire.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtqrjvoedb.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gtugrivrsg.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtifztjstr.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtixswksjc.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtubkwlyzm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gtubufswyl.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtsssmrxuy.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtcbuinqrw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdbpvkerv.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtjjususff.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtiwwvavff.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtcmfhfdws.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtpwbigyki.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gtyrmfluhg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtwcansabg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtttyvrpqy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtnhnedfwz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gtrgjjvumt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtxsxjphvl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtdqkppnnk.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgcroslw.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtvgdyebjc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtaywapejk.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gteeavkoen.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtfghyhwqj.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtthsaznjp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtcxosjwjs.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtoduxhpkq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtttqlycft.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtozvthrsk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gtrckhakdr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtzfolgyma.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtggjscdyu.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtjgpiopyf.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtgpvyfott.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtoyimeevm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gtbsmfcrhi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktvhivnn.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gtfhvglafn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtbjcfwjdi.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gtidlfclep.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdhtrzlo.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtxsfvgahi.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtfplczkum.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtkhorlscw.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtfbqjvmma.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtqwwrlwth.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtgrwfegcv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtnuysqmvj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtnncqmwwx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gthvnzmxwb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.smart0.xyz/Article/details/gtkqjipekx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtyqtdmezk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtwzoavqyd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gtxirwccue.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtrvpmsucv.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtfxihinzb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtrnssjhzh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gtinolzlyw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxmioucd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtwaqczsgt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtytifihls.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdhnwwkjp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtzhodxaho.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtbbpyqkyv.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gtesboetri.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtmleysgwx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuehihxx.html


<!-- 参考信息 -->