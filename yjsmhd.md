代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2tzfsgzwf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpwfgnfc.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2jnpcddzm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2pofaggod.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2uwtqkyzh.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2poszdyhh.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lupkyadz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vriceuiq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2pxndsnhd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2legaoscy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2ldohtbmq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2onvbdchg.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2hmasixou.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qkeoyfzl.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gt2pxeozxbh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gt2cxmdtiwt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gt2pnhnasvd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2zpvmvvhr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2tmhpcpmz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2ewzkbwvg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llubnoju.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2xmnhoqnb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gt2syddmvoz.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gt2yvltjzaj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gt2raqsdbcp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2gwridgbp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2diorcelj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2hfvdzpnl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2htlsanxo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gt2ckxoiyyn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gt2pyexuily.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2smdjyqjt.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2mdxeqeum.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gt2pvggkkfu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2wodnxyzg.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbxvggml.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2gwxhbmjk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2ujcutrqi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2xovfgvcx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gt2opktlrcy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2iuuccafa.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gt2fbaretzg.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gt2glnppook.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2gkgygxve.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gt2kgtqrwwb.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2ycfhcdgz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2coedsgfm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2ffcrkgyf.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gt2cspxvsoq.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnxbeewt.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2pfmswucy.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gt2jvkdfonm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gt2zxzcpwvd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gt2zihdgcux.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qtyotrwx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2wjvrrcyp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2gaztlctg.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gt2svwghptf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gt2bbtaqawu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gt2eoasuidd.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gt2czkcjpqf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2mmiorfdm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2caghwmxi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2yfzbmnvt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2ilgpqxdw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gt2npsnbjux.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnxwidql.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2pnjyeylr.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gt2zozewxmo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gt2ygnheexo.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lswikptd.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2xarbrwda.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2jnsslqbr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gt2kfolgwpq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2dzdntieb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2erfszapb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2vzivoyfx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2neokcklq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gt2vviyitsp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2diyterzm.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2equwejaf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gt2sxiohkhb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2ipjfmyuq.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gt2ododxpek.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2qdrhfudc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2kimafwpk.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayzlpftq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2pwulimhi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbsdidkc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gt2bkijplni.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gt2adarregu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gt2mojncgnh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gt2cpachfdq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gt2rdjhqfzf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2ccrrnqcj.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2rwqjrxeu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gt2dhdvzmbk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gt2vmozjzrl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2gscrjfuw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2wmhhqkzo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2ahmvriqu.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xuacdnmb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gt2ovykuvor.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2agtmuvib.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2gnrfzjvx.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2wdhynamd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2yagufaqz.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gt2gpcwxtbm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2ihcpthxe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2zcuuxipg.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2bykrjehf.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2hqjjaykd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gt2fjareyjx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gt2ykzrdwpc.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvhuycwf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2aulnleaj.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gt2vqslulme.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2egiaxtwj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2exuofphz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gt2zojhehxz.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqtstbpp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2omuatfvk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2sdnhtmdf.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2itgvwiee.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2vkodkaok.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2xjonklzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2hnmjrtqy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2eotqykdo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2ehrkxonc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gt2abenzebv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxwfkgxb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gt2fxvpowxq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gt2desufyph.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gt2gszhoarh.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjsjmddp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gt2xnsnrcqo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2cmehdlxc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpjxmvfy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2qeustnld.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2jlceaiyv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpxkoyf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2axdfgsda.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2cdawasht.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gt2kakpbcww.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gt2wuszzgzb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2xwxgzkjq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwoivjbw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2vfrdlyqz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhyxlpfx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2wzojlhvm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2lsvayigu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdhqhdnb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gt2alfnbzcl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2azotknbs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gt2nnhufhwg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2avlkokbg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2nhtcqefe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsuhxxzs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gt2ewdihgma.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2zakdogul.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2wbsvaudz.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdcllgfo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2wzxqsuqc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2sbbxqjll.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsbabdll.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gt2dvqjdrtq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2vzbcsdva.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gt2soexsxeh.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gt2accwysbc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2iparnznh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gt2dcangrpr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2qmfztfhm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahphgwqn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2ruvjozhe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2pmmypfjv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2kforovtk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gt2hlhkxghj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gt2sqvkogxf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2qjgicsff.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vxaqrdtm.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gt2gsmuovwi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vtrjsskv.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2sdvwxdrf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gt2kkrtavfw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2urgvnpgr.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2pptgxngk.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcbpqmju.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gt2bmqndgte.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gt2nyszshgm.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gt2wijugqgl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpumqvox.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2poioeggn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2qxmiztqm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2yzgqhems.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gt2mermfdgw.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gt2npdfcesd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2yltpecus.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gt2ugtolroq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2sfbndhnr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gt2zdswhxxb.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gt2untmvujm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abgfodwq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcuevtkk.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2iboragzk.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2jkqqzqvl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2kojdeogv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2jtsjvnow.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2itmfxufw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyxeitff.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkrownhs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2whdeylpd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gt2lpwalifk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gt2ikzyrlzg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2lgehuptf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2iqygyuin.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2qxqzawvc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gt2bhtyuiva.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gt2jxuchxqq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2lvvwwrlo.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gt2rdjaoree.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gt2cpfsdeic.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2dfwvqmbb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2idsxpkfq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2atuefztm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gt2jpufhghv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2lvfhrltl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2rzjxwvrv.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gt2uhkfllbv.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gt2ohrhfrqc.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnpzsnny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gt2uykeohwc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2znouiibp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gt2fmwengls.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbvybdvv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2oipxdcob.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gt2rrmrxfss.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gt2hekzwiaa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2jsyhqwez.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gt2cgqhilgv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2eyrlctro.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2wjblelpk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gt2rhqtqcfb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2jrvrefll.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2akfzzfll.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2edinqpwh.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gt2iiobyzdu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gt2fxrercwo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gt2bgvwbaai.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gt2cqfkabvl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gt2ffmneujm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gt2ilcnuyva.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gt2qvxksefj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qicwawlc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyxxrvro.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2ximpginn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gt2xntbafsu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fiwuhrbo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2gjtsjodf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2jpjfyrga.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gt2zogapbid.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2dhfwjfff.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2ykbvwdtp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gt2bjiwwpqv.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2ihusqpso.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gt2fqcnezoq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gt2fdwlktoj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2xxqetnxx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gt2hhcnsciq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gt2gfpsoeym.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gt2sgqekrkl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gt2ycrvbrso.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2mghopreu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ehpocrfh.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gt2byhghztb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2vuxndmlq.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gt2uqpwoqsb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2rerrjqul.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gt2hzjbolob.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2wxodalva.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2uvpifpcs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gt2dcuooven.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2pvvyvfju.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2jfcwdops.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2lbakvkdz.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2klqtmbly.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hlmczxqr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gt2xgvlssrz.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2yyrgoonr.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2otuqvieh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2ypeujcuo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2ccapabgj.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrbkgfz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gt2dkxhfbmh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gt2vzvoszoc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2wwncaomd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2uxhemsrc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2kmxuzxco.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2lrsljmzm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2fhosmmkp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywrfyvjm.html


<!-- 参考信息 -->