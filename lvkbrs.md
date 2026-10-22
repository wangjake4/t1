代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2ucqwhoyx.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2jigmemow.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2szrpstwg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gt2vgngkjmp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlzsirqj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2chkytfsi.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gt2xfvvmiry.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2dmyqdqoz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2fhumazbu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2yjfxxzad.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2afrwhqqw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2jnkopzhf.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gt2weltwhvl.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2wmmmrfdd.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ulknlqdt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gt2wydlaubr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oruciuce.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gt2tsomlhit.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gt2pwqwlsah.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2chtlzxyv.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2vuievvma.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2pzfigyaq.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2gxeqfypc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsxlgqrv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gt2lybeniri.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2rvrbmnph.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2ykrnaylp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gt2mudbcvll.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gt2pxnezbwi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2vxpntrxd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2mdkebnao.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gt2lflgsiyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gt2etclhwol.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2mxghbiqv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2zarttmvf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2xhluyvag.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2oblvveih.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2cdekyqkr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2ycbtabti.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2hizvtmge.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2clhnnfez.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gt2fjpdprat.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2lukqceor.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2bqvqbubx.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2lhyyltli.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2llnxwwzl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gt2nqzbiprq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gt2aixxmqpj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2ugpyebhj.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gt2topknpbc.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2sawpsjqm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2jxavwqes.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2fzbxpuqp.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2qwhnagtx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2fznmkidp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gt2hrkawyhn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gt2kdhbpqhw.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2odjsaalp.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gt2kjxbenlk.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2wjwfshyy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gt2fmdqvswf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2vhomdfij.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2phcjbchd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tknpmvje.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gt2zxxieuqs.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gt2vpdelhgr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhitgxva.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gt2ikkouork.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gt2wfwoeary.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2vgxgtqlq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2krzallle.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2hggqazrf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gt2kswhjfft.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2gjgarcvo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdxhutl.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgaicsul.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gt2tjgpgmoy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gt2ykebijxo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgdqayt.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqqtoulo.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2qfnirunb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2vmjtvhdr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2sywhhplh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2evsiptta.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2pdjdgsnn.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gt2fpajhmbr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xodjmumu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gt2fildrpob.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2ohidmkop.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebsfuocw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gt2jydmngzp.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gt2zvlhjxaa.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gt2lbaqxdwk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gt2qvhlgogb.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gt2dqwvhieb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gt2nrdduign.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2zqtnwfwr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gt2doqreacw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2uspecsut.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gt2qttmeust.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2gyfwqkcb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gt2sydwoziz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gt2hcmisfdi.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2xukoacfq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gt2myeyjbpi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gt2dutsmnae.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2tubwoqth.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2vetatphg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gt2ratnjomn.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2ghvbeheb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gt2vjazzohc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2lwxeybua.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2vxzfuoit.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gt2pxisasgo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xhfcgojy.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gt2duntsgco.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gt2gmdsrivl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2hdemlfms.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2jimkyfxf.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2yphpynjg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gt2edqalvtp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2tqdfdmzb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2yraefhxb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2wltmfptl.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2foridpvt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2appdzgzw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gt2ekixsagf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gt2fazhndjt.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gt2mfprvtip.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2ptdooawl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2etceoesa.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2tajjlfix.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gt2ficzdxqi.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2swpysbql.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ecoiegop.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2sovirnod.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gt2xfpfjeaq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gt2xdpxxxaa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gt2cnensrfl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gt2syymwpcu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2qxcjeimr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdtiaxiy.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2kcomtopc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2khnozjvu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2gzzvhygu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gt2rthqgsld.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2vsictxzm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afenllah.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2rbvazraw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gt2bfthzbol.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gt2bgltscqu.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evlwxwly.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gt2pufgvmnr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2lkhrzyxm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2efwewfae.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2nkcukusv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gt2mtjdeqmv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2arbaortd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2bochycwu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2cbduwvtw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gt2yhinmhxx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2qjiosmdy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2pvvnmgpa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2prudbeur.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbxeootj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2nesqpxfj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2wnhzeans.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gt2oksembhl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2haoonijn.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2lockkqzr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2xybnygps.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2qdyvcgap.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gt2knxwjknb.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gt2acrfyhsn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gt2mhxdyhmn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gt2ubxvawtc.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gt2twvfbhfw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gt2ffoqjosa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2fzvtxnxl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2goasorux.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2zxexfxcw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2ckdyzszm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2lrwpmpky.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejteuxpn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gt2unlnxoqp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbasswwv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2fosuddtj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kssnpkfx.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcdfqyjr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2illdfkew.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgdpetmu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gt2xxwfxpuy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqnbmhst.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2dzppbrds.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2yvwzncsu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bomzqzyi.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zogzjsyo.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gt2cijvsupx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2qhgpkjfx.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2wywgzbxq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2ejjlhmdc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2jssahtyb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgvrjsqh.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2lcbbngac.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2qdnuhyyl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2yfylecjl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2vfbdxdea.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbbqqlxq.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gt2kkprxuka.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gt2mtfmfxft.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2cxbotycd.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2vlzubhon.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2vzolfuhs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2exipzqvj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2fnahqlqo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2kxemoveb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gt2edgnvmgh.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2cbxixibv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2uszdplan.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2kuwvisbl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jypxwhis.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxigxlxk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2eitqzkpc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2kbcojvtc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2nsfasysi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2zrkvuirc.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gt2oeitrvpf.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gt2bvziyqcg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gt2atsakkzp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2pmffezfi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2gcfpyvkb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqpcoahq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gt2zyrqhpvw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2jtdjfoyb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2uvhlmjun.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzvnjuol.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gt2dlomgwzi.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfvacnuw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gt2dkgaxrua.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwuvmjmi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gt2yunqjxnj.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2ktoedqrs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gt2okkoevht.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gt2fkthmxbw.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2urrqnseh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igzklrwp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqsfqeha.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2rbbdmqcd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2pqovypve.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2rxbvnngr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2hjkbtrpx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2wienhkpd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2tykbtrfq.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgthfqlq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2ufxjihrx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaxdeyuw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2mnaylnyy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2kwiqisvy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gt2nhgcrron.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvstjnsu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gt2rltspaad.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gt2qfaampev.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gt2cbzatubq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2xymdmdcj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gt2mybkrytt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2vukitepz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2myxwtjto.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2cbzmzfkt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgfuiiba.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2wqsothmf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2rhpingaf.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gt2fnqmjwgq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2rmsmleqo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gt2mmbobniz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gt2foyzhdqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ortkvuyf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gt2mgzykmgg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gt2pdqdevzg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2jqcksyit.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2yjjsxvlb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2anfmfjac.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gt2ucjrdndv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2gvzqybkv.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2weenkgfz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2aysfippv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2jlawzxyt.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ytlbiamt.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2imfbkovw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gt2wbuqvsup.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2mezhnjsx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2aoxfujlz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gt2dfqnrrzr.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gt2krxmjhuy.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2opzarhet.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gt2fhcrjuuh.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2awknnvdz.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2axgystpi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2dzicmckw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2xymnsdnu.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2cqbotyrv.html


<!-- 参考信息 -->