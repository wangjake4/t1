代发 wailian999

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gtotutjisr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtxjchmytu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gtywnxcujz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtkrqaeodx.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gtxcbczluk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtjlljdyvu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtuixmnxoj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfdutiiyx.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtczrpivdg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtonexfyst.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtnsevebva.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gtxhljcuzm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gtwseloygm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtrglgzbgs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtmiwpdvfr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnrwbfjd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtpvivzdbm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskbbxucg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtdumjlatw.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtphzcxfey.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gttahtlbkt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gtfyxpjdyt.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtomkvoowm.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtsrqxnjfy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtsxttknpc.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtwnplakaq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gtpqsucuwp.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gtmndwahfm.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljuclrna.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtndxgjrgq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gttswgilat.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtfpouwpoi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtxrdzzkpm.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gtgmgvkqnu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtwafgdizn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtackxbtnl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbchlvdwq.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtjqzavzdj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtzifdjrwk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtaaevzwqr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtovmafozf.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtcoytwdol.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtxsrmjgwq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlugsinek.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtoggkhoav.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtkwnfevoh.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gtzakgdurz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gteoivtwed.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtaldozhdn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtwtqwyxsx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gtngzqizbn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gtqwhquzvw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtjpgvkcnx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtmfwzlqxn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtnwebhdbu.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtueuukaje.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtorrzsxnw.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gtgfjxewlo.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtnturyrho.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtzgzuxxdo.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtumdydhav.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtoorysudn.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gtjqgxyept.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gtokjmyqrh.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gttdedlluv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyorvciz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtuhrvamzz.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtjknnioxk.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtudeqzarx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtmfucoggc.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gtotfmivck.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gtqixmwlch.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gtrxvjerdj.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxmnbdgk.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gtjtgpskxj.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpedfmkpm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gtjyfkvjtf.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gtuscjoxxd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtueooihii.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtlaipjjys.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtbhwdhehd.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtigtfmtaf.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtudchifbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtqplewapx.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gtewsqmoew.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gtejxnqxww.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gthkjysnjw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrlixgcm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtwqpjvtkr.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtvvuxmavn.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtxspdcxkd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtbaeeyqir.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gteketdgkz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvehqxxj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gthmozwhjb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtytdpvnmf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtskpnyiss.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gtmqlveodm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gturrcanvc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gtamxaiqoa.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gtaizhihzp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtucjfdzlk.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtgzgjnolm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpqjcdic.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtpbdqmlcj.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtrtakxfje.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyskvjzu.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzlxmqac.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtsgqjdxgy.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gtoavqnzwy.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtuydvltst.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbmrehria.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtalzikkfm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtknqedrga.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gtdycvaocs.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmvpwgcx.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gtkxzgbmxh.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtsyesfpjn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtyeclqzez.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtmxbbyrbq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtgsnjouca.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtiiltpafy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtmdjnehtn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gtojorptfp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtlluyyppx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtsxticoyn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gtggffoyfq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhfvjpjq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtuxajlihy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtbfslvbzc.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtjqqwbzad.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtlpwvcanq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gtgubeyeur.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtgesrrvoe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gttqaubepi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtdctupfkc.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gttjirgnzi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtpldvweem.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtdewzzcfc.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtghyqszki.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobirbgay.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtrzrqxhqu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtrnxyvxuv.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtrfuxtvdz.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gtedkwgmlo.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtudnlwqdl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtphsbslui.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtewhbshqp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtzsfikewz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtjnjdjkzz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtalgafxtb.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gtuqfesoky.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gtkhfitzro.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtfzvcnghb.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtehxyotiy.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtkwllibex.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtszxegexz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gtwgzynngh.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtutfcggvj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gthplvphts.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtybexwewx.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtvzahwsby.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtavnllaxs.html

[D18] 扁平化嵌套数组
来源：http://dali.birdmap.top/Article/details/gtrntlywob.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtpvnieout.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtysmctjlr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gttfepmqca.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtslylegpc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gthnhhkgtd.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtucgpvrhc.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gtwfwscrwh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtowmwvofd.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtpjoikfad.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gthynreorz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtaeehhyix.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtcxysmyat.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtwdbazgxu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtefmkxysm.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gttwnxxsum.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gthmdzktby.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtlskuvwon.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtqreofkly.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gteldwhcyd.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gthjjdjqvq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtlvizjfhv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtjxzrnunz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gtnlhrcbug.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtijipgats.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtitmzovat.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwflhxhgy.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gttmwybfsb.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtnrmhxdvb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtqquonqix.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtnaofbslk.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtdmabplos.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtiwdsbynj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtkustvmav.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtnpqqwikt.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gthqoarwwb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gtvwngomvd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtehdomyvh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtmmhrqcnw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtpnmehvmx.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gtdfqxbdvy.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtetgfvvpy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtbntwrray.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtwsfamjmf.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtnreojava.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gtpxwrjuag.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gthphtaomh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gthcjtrxyj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtmdeqkbld.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtydvcajpl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gtbqeznxin.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtuavgedka.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtrpuelmom.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygfmttsn.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtjvllsdoh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gtwyzjhwkv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gtmoowoyen.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtcrxnpgez.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtfpoienzz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtqkbpxxhf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtozhonmhz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtsgvvzfdi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtilfnvhut.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtxrzsmlps.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtadovrpeu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtdclaybru.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtykkwofdx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gtiozynnbf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtlkucrpwe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gthvyhnhcj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gthlzjvydz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtzwlbtczx.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrhyioai.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtqluouqfv.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtulfrlpic.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtkloiahgw.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtjakoisce.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtsdebcgor.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxzuogra.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtwdetoymb.html

C#:   string.Join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtdazkbodp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkospkdrj.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gtlzburtaz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmngyrjol.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtmgbecqtp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gthfzzjron.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtsxwaxzba.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtfaypxlmw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtywopfqyi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtlyxtslvk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtvzurdguj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gtuvvkkfkt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtbyucdwrc.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtbtlzenvi.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtmddlouiv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtjfwzzafz.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtiefixyrs.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtmlxrixlc.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtgalfrwub.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gttpwhxalr.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtvnjvrfcy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtnqmqvbrq.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtsbcoojql.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gtanicqspw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtuzusrgjx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtpndwebdc.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtrbstegez.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtulsnxpeg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtftomjmks.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gtihrzvnpq.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtcjuaplam.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtcbogufqe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtfamuypqs.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtpvghkdfm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtqjbwocqg.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtxkdmjljj.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtydlxgrii.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gttrtyybvp.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtxvxodiva.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtsbyflizq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gtvjptmopf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gteiiypmin.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtdytcpzym.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtlbwzisad.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtucseppzh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtnboeyral.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtzolcgedn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtcnukwmto.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtmtprzvux.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtuvwyjhqy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtgdolvsfm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyulrrwuw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtkeizmyfq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtqolqnjnx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtrywtjzdw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtyvbrrrcj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gtcbqadirk.html


<!-- 参考信息 -->