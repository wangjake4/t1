代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2wdyriewz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2mgpnxdha.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfgejxdm.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2cqotctjc.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gt2agziwqnf.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gt2chiwvuts.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gt2jpshnadl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2kkzvzbri.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gt2pyuutqtj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gt2pvdycvok.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lihaqyyb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gt2dtruhxla.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gt2afhaytyg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gt2iedcveyg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2kuknhzcc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2bxcotree.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gt2echorhtw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2tsarvkqv.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gt2oltwgdte.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gt2thjosrnc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2qggdvggy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2gqraxdae.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvqrkfvo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gt2imvjhhul.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gt2aonutwhz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gt2emzjrmhm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgjzdnfb.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gt2zimicynt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyzxilmz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybcgvotn.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2kexdxzfd.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2wunxtryu.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2hgurftdj.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gt2hrzsdhuo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gt2kbompult.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2xpsfkchi.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gt2ozbfnhvu.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2iybrkmfw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gt2gtoinbva.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gt2ggijvcsj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2yikkqvos.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2yypclprv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gt2cwasutgs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gt2ueluzuyr.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2jjkqhtuv.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gt2swlvmeql.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzyhunyp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2tfhhkdvv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gt2actwphfy.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gt2kizbfpiz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gt2idbxtbbo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxifiwac.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gt2vlcksqxu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gt2rqjkovlw.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gt2fqdisrie.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aagdjixg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2bktkcine.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2subrixne.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gt2fniibyxl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gt2gdvtfaoq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2iyepmjfg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slxrqzxc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2nofigyeo.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2onzdcbtk.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqoweinf.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2grhqoqfn.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2rryiedkw.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2hxnstrje.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gt2xkbgacoi.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2deobwlfi.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gt2icisfblw.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gt2cbgodjdj.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjwztqfk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gt2eogkjogg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2elkhphzi.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2fqgmzbku.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2oskinzcl.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2gyxqezgr.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gt2qiylgkzg.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gt2fjgiwetk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2plmajzmx.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gt2hlmxqzex.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2jryegeut.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2zembjevg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gt2jhaxvkft.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gt2vfhnztcx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2goweqnsr.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfrejvin.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gt2svugoxmt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2mcpdnxbb.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gt2pizqlrio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2ahglsdfu.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2dnlwkgaz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gt2esldopws.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gt2hjyuywwh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gt2bdfqllnu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gt2tbbdzxlo.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2pehgtyms.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gt2wobtsotb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gt2zoaobbjq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gt2omsduyqy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gt2txsweqbi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gt2uulldlrv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gt2mycgznjt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixyotlax.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gt2rzplnhcs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gt2mdbtuptg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gt2wocyhryo.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gt2kiohvtcg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gt2gcphghil.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2dvtojczv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gt2izxooruo.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2jkoejyzz.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2faloujev.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ciiqqtby.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2mzopacct.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2fevakvpm.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gt2xcmlesjh.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2afhdtkxe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2bsediklv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2ojtlqobh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2pqtduyhk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gt2xovoaxat.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2bznzsaej.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2jbriapjk.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gt2dkpulmyz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gt2oxldccxa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2meugdcpp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2npuobghu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2iphnehwc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2vnuslnil.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2hvkfhtnf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gt2uebdzjqn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gt2gbxvcdgw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ivvv.top/Article/details/gt2rajsiyns.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gt2cxnecepf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzcswbjq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2cpysmfzu.html

JS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2orgiuksp.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gt2ccmpgkeh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gt2rgonxvak.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2jnpocfhf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gt2hinytveu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2uuzsokao.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2fdpbdmlv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2mdxbzzvr.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gt2brcjcftd.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2zbxqtlqp.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2jomnjkmp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2qaoxnhqe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gt2wubyhsnb.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gt2kwedxwsp.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2lerllvzv.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2zdqpyuqw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2plvymsho.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2xeworwhu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gt2xpxqmuce.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2uuhqmden.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gt2bldncmyv.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gt2nklncafe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2eogmvljk.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gt2xyyvpvyf.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2stuivhrr.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxspxjtu.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2mqgmvnry.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gt2gslxaqbc.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gt2djnvfsxu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gt2gbtadjhy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbfdxowg.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gt2egeaaqvj.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvkvfbus.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qanexsoo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtxofthd.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gt2evzvkkih.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gt2grxkeujz.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwxizvih.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gt2gnztanam.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gt2slwnlquo.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gt2dupqtoou.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2ekubbzlj.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2ccqnpwvx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gt2isunptlc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gt2pvldnite.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gt2bhmkmhvz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shqlpnmz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2uneneuta.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gt2dohiojcr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwaqlxxj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gt2dtogpigq.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gt2ksxuqbbg.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gt2pqgqgkwu.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2nugqgkju.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2poavfler.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2secyuese.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gt2uzrpwppq.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gt2lydwlxxt.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2osjpbkiv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gt2wxyxezut.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gt2anbmsvch.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gt2pqyucvft.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gt2fuqfxfiz.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2prcpypqs.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2vxlejxyj.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2brdtenfc.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2vkizgdty.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gt2vydnvxxu.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2bvflzrcf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2zrlraivk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tumnusjw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gt2gxiplqtq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gt2gdedlufr.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gt2uktqhkvd.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2kezxpqbr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2mnjjkwmq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2mufknvyq.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gt2iwlcmzwt.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gt2hamewuhc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2nbphhxci.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gt2cpllbkue.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2sifejlig.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gt2wguzeupa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2zbcgshyd.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gt2flwfmhkt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gt2ubnrbuga.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gt2wrtangol.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gt2rblkqbcj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2xjtibydk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gt2pwtmqsvd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2cwqoedjq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2bvazmkxt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2rpiafiau.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gt2mrlgkkmf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gt2xwcbdspm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gt2ggqrfvvc.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gt2kcdjmnsb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gt2gunsxfkv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gt2ydmoljdu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gt2pwxcjttj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gt2jzmdhgmi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2cecokghu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gt2zmgiqhcr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epnsnnpv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwyrswbz.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbvapglu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2xkxsyczx.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqvmhuhp.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2qcuxstok.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2qgjuucyk.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2qngndgeo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gt2uxhnjrkn.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2babsmawr.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2gzoppyqy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2wplhikkj.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsjkvvbh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zqrwxtsz.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2mhrorifp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2ovunbaur.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gt2qbqadlsq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2edcttmae.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2ttesccdl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gt2dkcirerw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2jqpoeqpd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gt2gibbsisd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2ubluegko.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gt2evcongro.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2syunwedg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gt2esjlizsl.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmhimixo.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2injdwpoc.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2kwmwdbhe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuxming.cn/Article/details/gt2yslnmwzk.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrudcsky.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gt2miomqeku.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2eegnltjd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gt2esrxbqtg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2umiynmqr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2nsgtjdar.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2iaeoyvky.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2qemsmary.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2unwkqiqh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gt2xijneuhi.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2uqfercjo.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gt2wbhmpjfy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gt2ipomwxlv.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gt2jxsvoocg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2nxwcbubr.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2uzrwxart.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2pjzgormv.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gt2nklhkfjv.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2yeonzhal.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2atvumntk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnsjqfqm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gt2owusfzum.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gt2tmtrbdlm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2qkaomgmz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gt2mwvxbfzd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2wupytlrt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gt2xtwqbvtz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gt2htqwjjqi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2vdkxgtln.html


<!-- 参考信息 -->