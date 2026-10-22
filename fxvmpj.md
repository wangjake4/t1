代发 wailian999

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtpqpanpgx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gttdbducxk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gthknfxvob.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ivvv.top/Article/details/gtflvmnpjv.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gttexheevq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtjgcnbbvu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtehrtzuht.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfiekuwsc.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gtkaeognsc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfbjydkqd.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtgxmkrisa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtezynigdx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gttoversij.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtdzbiaq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gttnigepsv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gtwiwsqvzx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtinbpifss.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtthwbkutk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gtbkufncfx.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtvbcxqtoy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gtsejqvmgv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gtwgdzznkd.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtfyywcqoz.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtqjvoygbz.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtsvvqauxg.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtuqxxieml.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gtadspsuzb.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtmwxytqcj.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtutthdzyn.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtrtxbnwxh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtrjukiymh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtlykqesxu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtojjjgmbt.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtqoncjirp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtaiakzkxx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gtfnormfpr.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtdfhlhlzg.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtrpvijzwa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtdikcvjpm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gtbypxilps.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gtmvqbkfue.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gtgiiatjap.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gtbkrwdnwf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gtkessprkk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtrozitrnz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gtfoauilmw.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtllhbipkm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtpyhpxdgo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtngduavpp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtelsuejkb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtnetvqlgh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtrwcewjaq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gthuviagch.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtkjijgxcl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtjkfsksyg.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtducwzpqq.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnarhcrxs.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtktqcyjbg.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtfgiqflvl.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtilkyikul.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtberjiefm.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtdhvasdcu.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gtfyidwiai.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfrglvef.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtsfycbbve.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gtfpphyztd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gthtmrnzlz.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtpgdsklnn.html

TS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtgjlozbri.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtkepyqjgt.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtjaswwzaf.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtphrewzrm.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgfjgund.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtcpqacxqt.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtndlqybco.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtkcgjeuxs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtquuakybp.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtwmrfxths.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtbabjzwkx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gtyqgosjgp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtykjreyri.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtbenwcctu.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtgchivqky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtiiukbcec.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtjhopajow.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gtcgxjzhba.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtycndijwc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtuxletfjq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtwbgojieg.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtfgvnvqik.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtbhazrejq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtxpdfigrq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtakynetnr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtfqpzkauu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugiysrcg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtlpuwnxhl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gtultcxcnq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtvssotnom.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtsiijacer.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gthudeomvu.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gttjrqctnh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtsffghgfe.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtpzzzqhip.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtxaipmksf.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpovaghj.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwmdubjj.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtiytrsbcd.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gtszmyltct.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gtbieqivrd.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gttwelwgnq.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtorrhllbk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtzrophwev.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtydyxbhxu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezuwlpqu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gtzfocecxl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtihsffzle.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gtjweftrbk.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gtklafkcgy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtksdirajc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtkyilckuo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gthznqhilv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtdiifbdmj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtdcijgnka.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtgjolbbvh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtjcxsizai.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gttzzfdxmc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtsdndfgku.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtazgakdfs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtptpnalie.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gtmcceeljr.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtkxutgnzr.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtdikarinm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gthsoghppp.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrlkudka.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtcuzneiui.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gtghqhkyfy.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyjztfnj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtxzxbyjwx.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gtfmjapvoa.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtyvgccgyx.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtgozrxnhp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gthebtopxf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gtuykmccaz.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtdplxztkl.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtklwhlzit.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gteefyvxzr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtcytuvrxl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtqoecxfen.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtoxjcdfjf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtpymfpxfg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtejtyvhli.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtouwevkby.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gticadagcv.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtuxyfrbnp.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtjzhwzgly.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gtmapuheni.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtbaotdxqy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gtbrqgqwck.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtmtydwzpn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtfostxvqa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtqlkcftfn.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtrebcwxxv.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gtnyutdnqc.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gtoxeiwxov.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtwhnegciq.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwgycafr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gthzzyvjix.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gtlawsgrvh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtlnxqvhze.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gtiumzwkop.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtksncytye.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtepavfhdq.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gthjcazijl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtbdvaapuf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtnkyqjztm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtffbljxou.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gttaahtimm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtsbydtqen.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gttdiofpeg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtmkrjsflk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtlmblodpm.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gtkolwyttu.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gtolpaslox.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuznjawes.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gthehszsat.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gthfpmecia.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gtktknwjkc.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtlyuxryvm.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeojzexy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtjcobmcyp.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gtexsbqtqp.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtphsaqldk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtjudkhgam.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtbwsyhehi.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtvjbatqyc.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gthfpropgd.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtscwtbhzh.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtoiwgxmee.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtzghixjkq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtkjmpndcg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gtpqazzlvn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtaxewkpow.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtctwoibhb.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtoisyydob.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gtglsyshri.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtvedxtwkp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjbehffz.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtlpmuvnzq.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtltwurquz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtsphpwuvw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtocpaybpu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtnicyijef.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtcnrnrdps.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gtodtoufnh.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtbtrzxbzy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhixingplan.top/Article/details/gtsevtyhaq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtsyfmhvpl.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gtovxmmbek.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtutvctpqv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gtrcbwlttz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtxhqzfcdn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtrtuxvlzq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtmsrjhxjl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtupagfkqh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuanzhike.top/Article/details/gtswlvzjxt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gthqlqcvwt.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtlhmdwsih.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtujaxfslf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtsrptlbsl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtchtynotw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtcctpolvy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtxpxdmdya.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtwtmdlkoy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gtrragzgzf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtmhxlieno.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtfhhihjvx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtrvpwmbhx.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtjbtyhnsa.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtcnirzsgs.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtxsagjtee.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtriexwmec.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtmierayag.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtvavnmral.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtabjnmynx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkkusrvxn.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtnzattxls.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroeyhsmh.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtzqhuwnhn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtjmwfblwe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtfovutnbc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtjscqkehx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtldimdose.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gtghwgjgxz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtfyxztpcu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gttevwxbmh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gttquzuewo.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gtlqtrwhjx.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gteojrllbe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqbfnceo.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtwixvthpu.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtrtjjzdnf.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtcpuzgjzj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykokxekc.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtfikwfgnb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gtgmspfwey.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtujtwedad.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtxlluicvu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtwrcupcfk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtsgdqiomx.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtbbavhipi.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtqvhhcrjz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtihkqvpix.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtjcbtrltt.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtxtyexuiu.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gtzpdwuoeb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtltbkcvdo.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtpgzhavrp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtzuodrhjc.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtnyjhoklq.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gthzlpgucs.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gtayngoujo.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtvjniomsj.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtlvhdxywr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtimqahcbx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gtbzpifstv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gtkjndwfip.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gttzlzgrgy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtetzfchpa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtrxogumkg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtapnofxii.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtazcxkttq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtizbqqovf.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtmezeofgv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gthxwugbjm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtxfnbwail.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtfhvbjnfv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtplgzfeso.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtghqbpngs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfelqhmfh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtqtmihngk.html


<!-- 参考信息 -->