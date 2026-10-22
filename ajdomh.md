代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asquiwpf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gt2ttzrmstw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmmgbeb.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2jslilimx.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gt2mqheebth.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gt2snjmlgpl.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqtwjnlv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gt2dkxfmmjc.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gt2vsqsarpt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gt2oukedhbh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyvvalzv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2qxxdydpf.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gt2frzlhwam.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gt2hpnzimvk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yueranfly.top/Article/details/gt2oiwulqaq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jmfhnfgj.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gt2lktxcfpi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgrwcxov.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2qmzderjs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gt2jopyjuro.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2fwmujuvn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2jltkptox.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gt2lfliibhv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gt2bstazpuy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gt2owldvkvn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2pvenrobm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gt2pugizunf.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozokkfqz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gt2mzujqskj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2zxywmfxw.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzbzcukr.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2dtcijljy.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2pjmfuflr.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2awifcsxm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gt2rsmsvvdl.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2vgczoofn.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gt2sdtodjit.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2fpunpuqh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzjtlozx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gt2cfiuekbk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrwtjfsl.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2lybcfpxa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogkaxdod.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gt2kocpwldz.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2fcecgbnx.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gt2dzhklcmq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gt2uykegkrk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gt2qfljfmgc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gt2yexwuzwx.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gt2bjjawphx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2xcfqapsy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbjnjjtz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2umobwtoh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gt2ekdbbcfe.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2yhbipkqh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2gzouhjpq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2eqcvtafv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2siogslqo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gt2zttiqhhs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gt2mcwvewii.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2jfthnbcb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2elbdgeup.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2jgqedhnc.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2oywxfkhs.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpjkpjxa.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gt2ifriznxi.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2fyqwicqr.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2xylfndny.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gt2jzsklfsq.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2pdnjyqki.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gt2coeznedg.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2yeeigymk.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gt2fwcnzlhh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2pprotgql.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2bbvsyxdr.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2cyiwpgqb.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2stygvogf.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2wrgujrqc.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gt2yhgamewm.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gt2cycnmoih.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2rmpxqsik.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gt2vmvzgvqm.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gt2powjattu.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gt2zjukmddp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gt2kbcogdco.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gt2dqdejond.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gt2ydfnkfxj.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2paiykrth.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gt2nsdwemru.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2ianhkxde.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gt2ohyqcqph.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pweqlmqn.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2gclezrsr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gt2zgwbgprv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gt2uklgeepe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gt2noctlynk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2eeoesaif.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2huoygaki.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gt2rtprwxeb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2hapoaopd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2uxjfzlos.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2aeurkunk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2dznaanwb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gt2iixjptnh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gt2atmrltun.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gt2okhocmdb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhkxeofh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gt2loynbeat.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdbgrtqj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gt2djgnobjj.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gt2lldnwiqs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gt2mzsaqjfy.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gt2ukamkomo.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gt2ckugfaav.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gt2xwnutdmp.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gt2ijgwkzpw.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tiokwkdp.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gt2teexdoud.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gt2wahzyduw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2qoypboxd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2ezpciade.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2civifmkp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylljuisf.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2sykpuklu.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxkusldg.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2xyjmgdvo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gt2nvfjzbxp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2cqziryfm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2voqkgass.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2nrrocmfa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gt2czwuilje.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gt2fsfuwrbq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gt2ajtcpvpo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psitgxel.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2uvvhftly.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gt2szdkcvix.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gt2lxumowvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2jbpzvcqo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qifebpxi.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2urejupzv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gt2oamekuwg.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2ndefwcrv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kksvpnaw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysssyesy.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gt2sshztfed.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2zovrwpwu.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gt2xfxpyapk.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gt2wchnivxv.html

TS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2swezutbi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gt2cfheswnc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gt2dxvljlhb.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gt2uifpfqua.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2uyhpopdw.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gt2smyvllir.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2iscocegz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gt2jazformv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2zdskexyo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2bsvqixqo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jyoumei.cn/Article/details/gt2tkgbvruz.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blenqtht.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcecnamx.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gt2axfnzlaa.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2haomilih.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gt2tahqkmbb.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2tyhrictf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gt2kilnfkmr.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gt2fnwkprct.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2wtfrhgvz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2xlyfhqcu.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gt2bzgkaztu.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gt2zxdzmtcj.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gt2fwcrpwut.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gt2yvqrxxqk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gt2xxueglcd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gt2mmigfjwq.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gt2tsxvyrlt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmkioqdr.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2ialtadrn.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2ffcqpeio.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2rsznwkbn.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gt2qxecuwnj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gt2dsrcavym.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gt2jkknsacx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gt2jwidkyux.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2dfdzyced.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gt2tcrmspsk.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gt2tlsapqfu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gt2tzeyujte.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gt2dadldawa.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gt2brqrrlgd.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2atqlruza.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2bmalgitk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2abupzqog.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2uvsspilu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gt2ahauquxa.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gt2rsmwwaos.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gt2mpixriai.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gt2omazlfqj.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gt2kulvuwtx.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gt2jiganphx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2hqadbrwr.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2pwzdffkl.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2dwlodzvj.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2prkdgyys.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2cwucbqlp.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gt2sracttiq.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2ngyvlmqk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gt2ezrumokh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gt2wjxnontz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gt2qxyzpczx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gt2bbhkgoud.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtwraryq.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gt2ocwifarh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gt2oatdzguw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gt2ztwengix.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gt2arsiyrzt.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gt2pursjxsw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gt2zuqiwatz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gt2nukesytq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2vwckinnk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egbhbvkd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2smjvjvyw.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvamtrzx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gt2qvmkvhzd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhxlyusa.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gt2vkttitdg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2upvaotwy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gt2vtyhvdsu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gt2edfsptqc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2xthsstgv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbwtiooc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gt2rewdaelz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gt2eqzikkrf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2idscbbry.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqjqplvb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gt2kbliiicg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gt2qwukflze.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gt2zvljatox.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gt2ofjmaaub.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gt2bptxtzvk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gt2clbwxsgx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gt2wobtascc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2favykqcu.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2itknyxdr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2yrfaphdo.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2khwmotqy.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2gnphhsrj.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2opasqvix.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2ertbijyl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2napumwkq.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2flgtqllx.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2gqwwqxqw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2dipeqhls.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmnpxhdb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xojbydgc.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2mevqjqwq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gt2jwgvmlws.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gt2msmuttxu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2cgwnkkiz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gt2dlkxysul.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gt2bjsbgetb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gt2znpvwcmz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gt2djhqemaa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2disxzbnv.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gt2lmnorxem.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2galzxhew.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gt2qfgzpyon.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2zdbspthg.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbkenhkv.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2nvcpfrbz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gt2uvksqjqd.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2uggoxihy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkuluhjc.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2juqklprq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gt2irokybox.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2sbmfkhuj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2htaftjeq.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2szvvumxd.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2mbsdmxtj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2jucqbgrr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gt2ifxjswrp.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gt2neophbhk.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gt2fhpufqpx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2axksotrx.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwwbtkop.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gt2arsiospz.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsbkbnxs.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2xhkgnaow.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gt2yuzsjqcz.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2hradnzyu.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2xwakjmxg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gt2ghyllxpd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2effihwpn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2vzxjgdtx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2zdsiamys.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gt2wnpfwngk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2ycbmybnp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gt2fyqjuwyo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gt2cyscdhtc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2fuaixmrl.html


<!-- 参考信息 -->