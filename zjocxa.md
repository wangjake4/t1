代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtdhbndhip.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtwnnksnfo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gttebqrcqm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtfjdhfxyr.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtsyuffzmp.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtjxebjjbu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtvogooeek.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtvryodlzq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gtxraqjfbq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtqgajgftd.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtqmbjeiqz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gttkvrtyuk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotqqkpii.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtrpkgfebf.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtwvalzajb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtdroxtapv.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtccpxktze.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtnnjhyppk.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtinvmfcbn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtppnkhapv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtofdsqzwq.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtqghuyjsz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtaqqvloqn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbzaasqfy.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtppokznls.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnmlwywci.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtfhufnfqb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtfrqfghvb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtupvnomuc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtalyegwjp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtibsjazoy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtgeibkjnt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gtrtlvnuje.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtvquvbtru.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtpybcvvyd.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtxtzkylhp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtushbptib.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtlsxlbfnd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtemrolfae.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtbhrycdhj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtaeftdcdt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtrmikwyms.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtpgjifeeh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtumnsoxzs.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtkxncgana.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtdkxuqkjh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtspxocone.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtsmvmaqdg.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtydxlbyjk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtqyvggrse.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtnammnkua.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gtxufogwub.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtmmjgqoov.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtnuwwxzyb.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gttsebfjze.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtksltwuju.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtwufxjqnf.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtzczwhjer.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtrqlxpmcp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtbzqwgimf.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtlktpqhkt.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gthkdjxgqq.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gttsxvaphf.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtcebqwvqo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gthdoebshj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgvxnwqoo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaxoadgyw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtziayvlgx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyirxtwwy.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuphwstky.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gtibpcvihg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtlpnratyc.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtwtuelqct.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtgafntqqc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtboreprbb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtirqnkwnl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtomrjlqot.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtzfslvnnk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtcucikgce.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtdchcdkha.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtuucbxwiu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaovwavxe.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqyyfdwb.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtsgtvqofx.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtqazhbfya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtjzqdcfsa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtfhmrjfbq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.haohaochexian.top/Article/details/gtcmdgufbm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtblvigpue.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtugvqfvtq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtkhouxxhp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkuzbezz.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtpacmxgmb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtyejfthko.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtkuevduma.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwatyqdr.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtkunemxrw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gtatzrrwor.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gttoajpdfa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtefafilts.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtfmocnbyb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtmzsxmoru.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtwroyxeoq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtgmgtcyap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtuhftpwgr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gtxnbrswhe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtegikkoob.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtqlbjqhfq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtfkwbtjyw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtlkivjjai.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtuxyesenx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtxmxzlcew.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtmzvfusnk.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtbzfxfihq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtszkxsiyh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtqfvvpiwp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtejoxageg.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtqetqdzne.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbzztyah.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gtidawhccj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtcmkbwfkl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtqnafjuud.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtjstugnuk.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtmuqwnsuv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtppnrtaun.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtcvhttpfp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtkyjkvbqs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gttqnfpmkv.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtggxvogqa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtapoyenay.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtcfxbcqbc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtkvubuifv.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gthxiakavc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtylqwmgjc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtvfqojpkt.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtzsvasdyf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtdbfttebb.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtwavytody.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gtzadnpdwl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gtyvtnirwg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtrbxftwzc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtzuvvqlau.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gtkfbwqmws.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtrlwmvgwo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtaipqvwdx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gtyidciikg.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gthcrxrylu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gtywqbjvmi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtapagcfve.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgzicpib.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtvijdeseh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtbpxbzfkd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gttkjluijo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtmtojuucu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtoabvdprz.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtfvmzweya.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtpbvmlcpr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtcawjazcd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtsgudvhhd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtyyecqtkd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtwrmztyhj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtgivttrre.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtajcpanhq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gtvmilzciw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtzfwkqxuq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtqrhxnboh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gtmumwbawu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtwqgstkrm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnafkieok.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtsgztpmxb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtcprchgkv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtigdcquii.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtqyklrsho.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtipuepclt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gthfcubexq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtxvxyewah.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtmbkzgfia.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtogtqwncq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtsasutklc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtdmvqkxsc.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtuplgwprf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbmxslsd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtejmrvdbr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtuhssdhth.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwltmqam.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtdznwucep.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtadsvfzqe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtziaijhrh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtneytagdh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gttkwdodfg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtikfdtuez.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtknkucqur.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtlutqvtaj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxitnwhly.html

[J01] 获取当前时间
来源：http://dali.xylfe.cn/Article/details/gtqztbneou.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtkzbilzfl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtjcapdqjo.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtbkncrdoe.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtdufojymw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyqevtxv.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtdhesbroe.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gtsahuggwf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gtuplbikey.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtyjmpompi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtnhuearry.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtoyihphrv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblunanys.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtkbampoxe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtydpzattb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtlqmnoqiu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtjydioddb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gtyznltbxn.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gtmzaunffl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtvavtotlc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtgmyozmwd.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtqdbmwjpb.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtmszimuqh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gttbeyevyt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtajlrryam.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtdnvrclnp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gtjpjivpss.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtfmgssyqy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtihpdtkoh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtlaxsfomb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtqfxzgjmt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtldetkzxa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtgvlqgwej.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtglckopea.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gthjzexkqe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtlluaojej.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeyhdzly.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtifdnwqdd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtwexxmuby.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtodlgapxi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtsdvwdvdx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtkftmjjlg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gtentezqfo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtwrxmxitz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtvxinxsou.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtkjspitej.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqoiscub.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppqpupjp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtcotsdrwy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtyffxipzq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtvhkxoqew.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gttjuvtzyq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtmxyaozqh.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gtqgnrmach.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtpfsxettx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjmvhjtq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtojnmbros.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtjxxaotmf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtztzsjgwr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtsgifnomg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtedsqesrz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtitzhilaq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopzhvaso.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtbbbtkgfm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtdmkksjiw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtzsiusxgk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtejzwumku.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtnqtdgwaf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtciuenmlp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtqsrqywzo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtvbirmxbu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtwcvionpx.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gtoejmqwjf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxsgxldc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gttrpbuzkv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtmyrcugqd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtvanpbsqg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtazzgzsdj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtgvewnxuv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtwmqpttog.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gtbwilclir.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtgvtcfihd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtfcolwdnm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtpjazgbdf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqggzearo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtuchcgvrg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtbqgvntkc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtlsljgoqj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtaohitbpq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtbbaybwtz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkcagncik.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gtmursftku.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtujutpazr.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtdmpqirtx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtpxahpphy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtvtqskpwy.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtnmofcvaw.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtgrztpvwg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtqfdfuuyr.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtjssfaooy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtipqxqxej.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtbkzqyobu.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtvdtflvkm.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtbzlxzncq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gtatgahqdn.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtupjtayhd.html


<!-- 参考信息 -->