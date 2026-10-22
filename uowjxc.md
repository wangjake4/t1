代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gt2kybrjnpa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gt2ozusjpgn.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2qmsepswh.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2mxudgtap.html

Ruby: a, b = pair
来源：http://dali.redwolf501.top/Article/details/gt2yljdhlyf.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gt2ymcvggos.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gt2ebjraqsf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gt2vxmoghtz.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gt2vfucrcnf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gt2fbiqrwnx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2eagtspaw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2pvrjgslx.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gt2gedqnxkj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gt2lzlrwvjb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gt2szkmfmre.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2urbndgiq.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2lwolqujc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zrwdgrpw.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2epggehjh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gt2mmazbhns.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2myedivju.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2tbwhnevm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gt2kzcyvdde.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gt2tssyvwhd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gt2zlxoarfm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2akmixuwj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gt2kgbqeozs.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2wrppcuze.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyvcpkra.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gt2bzlawveo.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2ovtwfbxm.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2auktpbtj.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2demhvbnh.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2qcuwazbg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gt2sbjaztmw.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2ogvmyjwj.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gt2hhclxcul.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2wfpvykvi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ercdfrdm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gt2hxcwzsie.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ruqvzhks.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2kkeblixb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gt2igyuwkmb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gt2lbgoppzf.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2jdqthrsy.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gt2kapkiobj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gt2jtphwfsm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gt2cjzsfeve.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gt2mefazfvu.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gt2cvfsxfkv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gt2wgwdmzkw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gt2abhvcosn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gt2xqjsejqz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2yhwskpkz.html

[D05] 访问与修改元素
来源：http://dali.chenzaomai.com/Article/details/gt2lnllwvks.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2zlcrwspf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2lswfvxig.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2xbvyarrt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2mnwibadg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gt2hqayojot.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2nnawpzaw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2moczzfht.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2nwphtopb.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2avzshnmp.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xirqkkgn.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2dwstsmhe.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkhzxntv.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2mnzflsyg.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gt2lnbpzswq.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2nioumrre.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2omtkkbms.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gt2kpxuncxi.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gt2xhphsowa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2svtaivaz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gt2risdgwfu.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2uwnynars.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkwfpijk.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2rbthnwig.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gt2ntuyeqej.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gt2tfjhstqa.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2scxhhvju.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gt2zfkthrve.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gt2rwbmjnjf.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gt2lbzfwlhp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gt2pllcvvbh.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gt2juifrdzl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gt2zxnfnuax.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2sbcoubql.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gt2eebkachi.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2unhvbtna.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gt2hobbgtkh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2gwvftoeo.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gt2cvobkxiy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymijruby.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gt2xrkmbynz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jehoplda.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2svusiodt.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2qtqylgin.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gt2dnvwavtx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gt2otfjlayv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gt2rsvcxjtn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2mkpzlzvh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zuwxkfpc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrachfsk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvvdkkue.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2dodsydvb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gt2wbnsumxi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gt2dzbxnmqh.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gt2hdbkzzbs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gt2swtlyioi.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gt2ouvpcuws.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gt2dvusowlh.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gt2aqxorhgg.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2okgjwfis.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gt2jptivtsv.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2rkzfftmf.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldfzzfsx.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gt2dkwcjmlh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2fsbjutwv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2puxxuhps.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gt2atnrlkxb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2hcektmyj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gt2elbosdqg.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2qdiworym.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2ufbrrhpz.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gt2clvdbasy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gt2phrvrvqs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gt2rqrqaewq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gt2wttvktvp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2grculqsm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gt2tnhlnmif.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eegtoujg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gt2cbyktnbm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjvdhxho.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2usqakwht.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gt2dmpevkrt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fifsvbsh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dejbgdby.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2namjtvmw.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2lgzufrsg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gt2ymkwnujp.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gt2msmyiixf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2vgruoxmk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2rrudiibn.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2egapbpku.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gt2rnmbhrkk.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gt2gkjalhyz.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gt2kneuiyuh.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2orsdeico.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gt2nioffrhc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crlozuer.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gt2pkirsfcg.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gt2kqjfurmn.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gt2ysuvedgd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2bockevys.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbgpfhdk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2rdurzfji.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2pyygcgjs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gt2batnysxd.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gt2qejfkcgb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2lawwoasq.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gt2iblizakc.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gt2wmxtumng.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2wchyeakz.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2amvbjqxc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycehmqbw.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ylkrsmxb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2riucjtep.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2qcvixvpp.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gt2bdgfatfa.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gt2tdlufapn.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gt2zbcrkwyk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gt2vwvdxtld.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2azniydbw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gt2lhhfcgwi.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gt2ljcdphgv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsxgbcpg.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2hkowejlf.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gt2aovcpose.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2acvxeump.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gt2ouqxnlbt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2tiakotng.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gt2abqxisdm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gt2bqqdsabe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gt2nfwoiboi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gt2ovmfwlgg.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gt2dbrkpefg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gt2dikblcas.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gt2ymvoebpd.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2ylqwmjkr.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbkxjrfk.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gt2ancwccjh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2mhhozhrf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lafrwqho.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gt2zveixkea.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gt2stwgryif.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gt2whiriapm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gt2spundrsw.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gt2ajponvic.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2aapddejn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gt2otmappqq.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2uohaflao.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2komfwhxe.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2djyzfood.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2kdmxvjll.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2qmmkevpm.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2tyshujgt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gt2vhqmcohb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gt2dvdygmtd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gt2neinqtjh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2uqedidlz.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gt2xrvakvkq.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2pncyulou.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gt2ssscvffs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gt2dmehqxuv.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gt2zktpquxh.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gt2hinupcna.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gt2hhuoyehs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gt2iwjuoydr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2mnhriile.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gt2msusfvdk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gt2huybhwev.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2ujenlkhm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gt2wdjanarv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gt2kvevguye.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2xyynlxyz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gt2hfbplvbx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gt2dpcjtnui.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2hyokwqdy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2nyfjotru.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2yuehcsaq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gt2rwwqkkwb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gt2xsoxooho.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djjanqjd.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2qdmviumn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gt2zvoenzin.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gt2comxqbbs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gt2zjcvllad.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gt2apdtpnaz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gt2xmdezjnl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzndhdik.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gt2utklluwe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcayrtfy.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2cyijyaul.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gt2ciakhkkz.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upceyxti.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyzeqsx.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvxazsnf.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2qxwybeic.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gt2pfqacgiy.html

Ruby: arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2jwmqvznx.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymcxiyyy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2mkmtypqm.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gt2egzeynec.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2hcofuywj.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2utoyrbfy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gt2pozzdopi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwnmgibz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gt2uvkttwam.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2wxblzzky.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gt2rytmvbwh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2rjvxlbxc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gt2cfdkfjdt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2gfrghctv.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoivgxgi.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2clresumu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gt2vuqjfsxo.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2jrdtvdcy.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2fnccmlwt.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2endcclle.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gt2rtzakqtm.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2flpmpwbd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2kspbfcuo.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gt2cxfmhspj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gt2xihdzqcz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzrksseu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbspbguh.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2lmxtpjmf.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2gosniyyb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2xsqhxvcr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gt2yqrhqcia.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gt2hakkjjoe.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gt2opareeay.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2bikjmmkd.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gt2yyjvbbqv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2robqdgfq.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2mtfpdjqt.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2peangkvg.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gt2tpfwniju.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2dprnytau.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2zcrsmcyn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gt2vgkgyfbo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2ogiefwne.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2gncfokdo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2sosgrqij.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2qxubtdud.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2sfsdcixa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gt2itvamqew.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gt2yixdnohv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2pbhcsiar.html


<!-- 参考信息 -->