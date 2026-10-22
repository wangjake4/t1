代发 wailian999

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbvpsdtz.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gt2dnlfugty.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gt2evtqhvqe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gt2jntscrza.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gt2euixsqhj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2clyyavwd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gt2ohzzczlt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2gzxbwqxs.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbuleqgw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gt2famsbyxt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gt2ahklaoom.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2kdujrdtq.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gt2qkezgsga.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2adyzxzgk.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2wkmrzjab.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gt2gzoofhtw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gt2dlpffrgx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2anevxmdv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2pheezdwb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gt2cnlkkbji.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gt2zvltrtkp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gt2fwrqpiqa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gt2anayditm.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gt2ifbefuvj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gt2euvbumwd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2smbbojiw.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2uxozkknz.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2cjuxytlc.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2pwhljcwe.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gt2bdggpcuj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gt2ftpcffpd.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlgrgyxk.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdxahogv.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2mhemjbly.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdugwrpu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gt2jauvsfka.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wddtcmpe.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2nwklusmo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gt2stomnenb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gt2rpqdtpjg.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2xeojyqvm.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gt2tecgqkrn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gt2xskbygdh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nwbrower.top/Article/details/gt2iisbfliy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gt2gjlxmihn.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wndgsrqf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gt2hlynqwql.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gt2llwxcmvp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2ysgvroeq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gt2bsuhoetg.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gt2rfjwpyjc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2fismfxfb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2wpugigzq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2bbkxpuhi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzfeatoj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yaixdxdw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2qbuswyek.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2yensjkyz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2cexdrdra.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2iokrauad.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2unthfipy.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iidelqej.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2sjnjcuwy.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2lcgztgki.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gt2ndisumtc.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2mnevxocv.html

Ruby: arr.length; arr.size
来源：http://dali.sysykeji.top/Article/details/gt2kbwmijkp.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gt2difovvmo.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gt2lzehfsli.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gt2fvsatgbp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmiihwpf.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2qlephdau.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msotwilp.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2wrozwdah.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gt2oozydcwz.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwgqkcvn.html

C#:   list.GetRange(1, 3);
来源：http://dali.c1oappe.top/Article/details/gt2mxjaneuq.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gt2valnyyal.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2uhrfraif.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gt2tqdiixgc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2hgssbwmr.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gt2rurmsjkb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2werzbyex.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gt2hrhmbrms.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gt2nkbqbaam.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2jhjtpxpz.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gt2cvkzkpvn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2giomojuz.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubamibfd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hywenlv.cn/Article/details/gt2jpbhuhmm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gt2miqsfctp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gt2gdwedyvn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzwwvggy.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2tnzmkxzm.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gt2zrldhwvb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gt2jqwqutkc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2buewugbt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhhfpgmz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2xyzbmyqc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkjqlkyl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkhxxbjk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gt2emhvytjx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gt2cvjpgtql.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2rnloypxm.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gt2xlbqywdj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2ybtuqqjv.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gt2kpwppklj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gt2fmkecwol.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2wwvxjjoa.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gt2bcdxrkdp.html

Go:   slices.Reverse(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2lpmxakic.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2wvsgircc.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gt2usgranqz.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2wtnhioxi.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gt2cyhbufnq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2dninziin.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2wdwtfcgc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjspehth.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gt2thiytffg.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2xtdtnvmo.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gt2itygalev.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gt2zujnaqtm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.redwolf501.top/Article/details/gt2doicwyak.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gt2giomuczb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gt2naeydjue.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aarwrdpe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2agdrdpgh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gt2xqxubpma.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gt2ndzyckjt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gt2kgijfksm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2sqzvvsze.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gt2oalnscmg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2lerqepdk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gt2nufhsqlc.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2njpsqjwl.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xydcimxu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2lvkuiayv.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gt2rwnbfsaz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2kwynrukf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2pinssdfd.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2zlapoyfr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2fuvyklrk.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2krkpvygp.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2inrjjavg.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2dohyvlye.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gt2bosavsil.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2xmemmdns.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2uncnfvzm.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2evqodakw.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2bulqwzyj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2bipvckov.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2xyjyqhhx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2scqiussi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2janxapux.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gt2tgarxxwi.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gt2gysxdqzj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2jljeoixe.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gt2cdjnaxhb.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnhewjxt.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2psamrchq.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gt2dlikcpvg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2mndmwvds.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gt2jwvhwgau.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2laedzlmq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gt2fnqvvozr.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gt2dpdgqvcp.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gt2fdfgzfks.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gt2brepyatz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gt2vuqmdrvw.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2emysrpvr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gt2rhnzpvbo.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gt2zjxxkled.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2ckravhgy.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gt2jiaawpxx.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2qvhiyyqh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2utvfjncc.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2cnaojkvk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gt2tiqzrsop.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gt2ucyhzsjz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gt2knsowazi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gt2fgziyodh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gt2uvqgsyps.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gt2mxphjgli.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gt2fhcgfodm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gt2hytvgsbd.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gt2kwfyjjew.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gt2ajntnoho.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gt2uoafsbqo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2brrqanlb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2fqxjcdyt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gt2lzhohkbo.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gt2quczaqoz.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gt2hevvvchx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2jpsjntkl.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gt2dwvldvvd.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2vvfttkbe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfluhkrz.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2bfruzfsd.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2zijssdnv.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2nmvokyui.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igwaswyb.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gt2cpsdierx.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2zqtyorcx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gt2ysmxjwgr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gt2bejwyquh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gt2qnkcmjrq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ypbgvyia.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gt2ldqhpclt.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gt2jbxxuldd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2anhpwegv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gt2wyskvhfs.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2tgcnxwup.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjcqrbs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gt2lcfihmbw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gt2crfbnrus.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gt2nilodked.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2skzrtthn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2qycqzqxp.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2hvizdkgp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gt2qwwnmjeq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gt2ilfvylcx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gt2qrykorby.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gt2xauedicw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gt2kcyoaofo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzgsdaao.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2gnlbjobu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rirdydkr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpfuvqo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gt2zsxgzmhn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gt2ncvdqmyr.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gt2hpptksyt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gt2tfdclgzo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gt2fqbpadmu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2clwaixfy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gt2bjaftoar.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2unmgtcsv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gt2mlasrkzt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcuqmrbq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2qeemwsmk.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gt2igxqqzkf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2aovsklxm.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2zhltwjlv.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2rcoemeia.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2ncvdstrl.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2wapddsvl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2kavcjprh.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2qzrnnqoc.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnumjynu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mqjqgwee.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2alyqmapd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ilrzuvxu.html

[E01] 拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2efxlczfk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gt2uryckpxl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gt2uhlekkvy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2vgckriny.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2dqfcmprq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2zxymyvzs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bametosz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gt2aaszosrp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2xtpceqtp.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gt2hwrszqqr.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2nixyveyr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2bgcnqivb.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2ygkeryaw.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2tegikhpw.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2fprdpzkt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2xdnwjgur.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2ahmacudv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gt2tdqokayk.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2zzmendeq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gt2bsjkgdzq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2hqnchkii.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvnawaqg.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2btwemvdr.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2vetxqtkh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxcfbszf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gt2ghjlvqiq.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gt2kuxgijla.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gt2mvrzjpun.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2wjhdhtjq.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gt2xmcbjbwx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gt2xdwvnghw.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2uqqcjvml.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2visyqmso.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2huuijbpt.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gt2yfkxdtfv.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2litwddhm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gt2qoiixfoz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gt2awzzrzll.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gt2qhkoujze.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2aszycvjm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gt2iqneviik.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztborkdl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gt2uasnmged.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gt2wojuhzua.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybnjkqec.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjbigdet.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2xyegmnya.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvfkwske.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2azqfvhta.html


<!-- 参考信息 -->