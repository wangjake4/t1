代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gt2dlamdyvn.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gt2llpobnom.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2tjvbfjcr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkenricy.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gt2tzxismvn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vjbhmqdr.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gt2irkljdqg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2eznobpbu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gt2ckgidevx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2hqqqaimv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwizzlok.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gt2dvlmvdvm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2zatvdidj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2ljafdiwn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nyjqgsks.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gt2awdvjdhp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gt2hhqgsbzd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2yqrudzkh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2wtekfnac.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2hvpihmeo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2ehgrrnyf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gt2ucvvtgqu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gt2nuynnfip.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2ryoxvjqs.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nofjycqw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2twbfyhqw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2wdclaobv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2sqbyspcu.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2blhsjabd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2lyupsegk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2dmghrwbw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gt2brhkhorx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2cqsyhbzq.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2cnzzafig.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gt2cvwnnmhc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhxilbzf.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2xuqxeaey.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2ykauxqfj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2wklpjgqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gt2xvpjpmll.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfomiukz.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gt2hrkbrmke.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2zlzlwdvt.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gt2dahtnegn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2svoynrdk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2frpscsot.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2hvdhdyot.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gt2wdujmgrh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gt2azpxulgq.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gt2curblmso.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2puaottlz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gt2eenrpqho.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gt2sggnjhom.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gt2ppzjxhpz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2rkxadfba.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2svkcwkku.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihawwgro.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gt2xhwcyyus.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gt2mlqebvlg.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2agcnfuey.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gt2eczeurho.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2pprcerby.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddtjulbg.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2nhbwjeiy.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2bmfzbfbc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2lmbqaflv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gt2vkakmjmu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gt2lhlwkczm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2occhcdpj.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gt2yuvmzdjs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gt2bidnafqh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gt2uiynkxil.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gt2oirmxetw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gt2knmtwant.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdnjxgxr.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsrawxnq.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gt2psbwcqoi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gt2csznhlsp.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2xmgekxpv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gt2epytbstf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dustcojt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gt2cehgxlnk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gt2ezgvwgsg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gt2premxypu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gt2rjvkrhhi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2jjlahvpa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2lomuhqvr.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gt2oefgqndh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjudayfu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2cyuxppbt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2qpgdqben.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2mjylckha.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gt2wjonnski.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tngkcfrm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gt2quaipyiv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2yuezrsje.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkbmkqbg.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2xfhtigwf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fbtvqbqd.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gt2lseycgvd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2ifxeycvj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2qzcpzqco.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2ecwkmmye.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2gxgsaczw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gt2lszstkwy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2embuqnit.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2tsrwywvj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2delzscks.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gt2bqprkqqx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2eifjjfgx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gt2trtomuza.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2gvgfphlw.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2xchcwjpt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2abasdrjb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oawfeiig.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2zzbejher.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2vxxbknrz.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gt2iwyrgcjz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2elwhhdgv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gt2rhcsrkjd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2fxxobfbh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gt2efyxyxno.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2pzdsaqkn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2noheycjz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2zqjgkyai.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gt2xjhthghb.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2abnwqrkw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2lqlcqawn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2ogkveogc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kavwjjuk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2vnfoimto.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2xdbrlkhq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2lduresmh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gt2ybnvbgmg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2qjkesevg.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gt2fmceezwe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gt2jicoiobp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gt2ofsbeaql.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2dfduurqg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2bpnijejn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2buxqbzkv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2nquhwexx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aimzgcqq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2aloogxyu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gt2ozojnfue.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2sdideris.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gt2gvzsbmxa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2wzagyswh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2rquzxcrz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrifenns.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfljqdkv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gt2dkakllss.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2dwdkiwae.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gt2hcpoppac.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2ctixwlwq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2edfcxloi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gt2owcclhav.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gt2akmalbha.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gt2rjuhodox.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gt2dptpbcjm.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2imygwerd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gt2oxmrewoy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2xzexcmix.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gt2udytcubd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2cpxledjh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2brrxcrhb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2hdxkllvx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2cqpelsls.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gt2jbclprfr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gt2zulehvvq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2fdsabkzh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2grfsfaxs.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gt2ztgmfqrn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2wsgonzgi.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2ksjlcfip.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gt2fkdksygt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2uuodvyur.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2vxbertrx.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2fhdtlefy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gt2xbianvpx.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gt2aamrejco.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2mmmjhcci.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilzhcpxi.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2nwosnnhc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2cvsgfiqb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2kobquuzd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2xjeshgla.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gt2fhilurlc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gt2fzrjlszv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2jsxpvohf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2yvgcbvel.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gt2xvruyvov.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gt2urfbscys.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2dmcciueu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2xpucpxnn.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2tlwtlavr.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixrianfk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2kmnykrei.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyzdysvo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2mxtzxlgd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gt2gkmolqbu.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gt2fcequhjn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2fcupnqzj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2vpxsalhl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2olrhxjuw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2sajpcwas.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gt2jcyqlthy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gt2hsxquwru.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2phhzdsdy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyfnotek.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gt2whyjwyti.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhdwkdlq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gt2hlomsmty.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2bhyxpxmp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2empzakah.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2mqvqflps.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2vbxrngwi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gt2ubodrtip.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2eocpihle.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gt2adopftil.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gt2txrlaebr.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2bohjgidt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gt2ydycpqiw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gt2ophgpdwu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2djvgrcyb.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgnqybjq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2yilrlvnw.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2korcfrdz.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gt2cjkqciqo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2brhniyas.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gt2rznznajo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2xmodiyps.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gt2pjymtmzk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2drwbcrvh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzhirmwg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2igiqjbra.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2sdmhaxju.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejckgdid.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gt2wffjyfyd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzavmsj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gt2lezytnhq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2vhhpmhhc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gt2gkuxufdg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gt2dyksqmqr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gt2irefazab.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2pframlmz.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2ulpibiew.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2amwjekpz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2ycnivond.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2xhgsjuyf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2lvhuxsgf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gt2vfhcemoc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gt2gtyewaoz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gt2dysddbpu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gt2lidoeykk.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gt2ligpmuxq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2dkxpspag.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gt2hegnqkou.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gt2wfxoziab.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gt2zldcghjq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2pxdomtfn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gt2xlbkwirq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2fgrfjnzt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2lcoteiii.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2iyohqpbu.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gt2rkahainj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2qewsxiat.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gt2vyyqzcur.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2lquewshv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2qyxptwxe.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uprhvehr.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2cchmnage.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gt2yurdckvv.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2fymmyghi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gt2wqnnfjnr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gt2bkpxlgtn.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpdncrmm.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2stcnaryl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2vvbepijr.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2mullekge.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2tlncpwut.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2xnhlppkd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2umrmzspn.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2tmlsoiqw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2fhbbxdce.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndkcqsrw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2vvschgyw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2npalqkka.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2ycvklpiq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2hpbefckc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2wezbgirl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gt2ctpcfxor.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2wmzhtvkp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gt2bhnricqt.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gt2qegywquy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gt2yagxjpyv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2hgiaqzec.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2jzvzjkwc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2gsxadyam.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2mveophhv.html


<!-- 参考信息 -->