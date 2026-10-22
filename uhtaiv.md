代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2gidrdvyu.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gt2kiyzeafm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2sewuuanr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2sanjtksi.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gt2gblwrnqz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qihjzjjw.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2ziisyacv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gt2dygrxapi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gt2xwbwyrit.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2ebyjkjda.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2idddioxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2yorxkxuj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gt2nhiwyidx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2inojheac.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gt2lkxvhizi.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gt2veooqiqb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gt2ggsjeazz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2rnbrxskp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2whocherc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjbzjglf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxogjcxo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gt2pjbhbpdt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2ylkaejlk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2fybtqnov.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gt2oisumhcz.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gt2zoxhbchs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2rafvhuyw.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2maynkktp.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2mlnlhibu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2lgnzjhsd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpnioqqb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2nyvfuucj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2oguwlfcr.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ehhqsowo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2gqqowjul.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2ioquinso.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2qydemdye.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axswbjfs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkcghxqd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gt2cqiqtbvy.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwpptgqe.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2ygnnaisv.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gt2shnhnmel.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2pkzfhqwb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2bojdeaqa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2bewkdwfz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nonnnane.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2akmdjbsh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2ajxseybj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gt2rcumipbj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gt2tpdqrbhm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqloczih.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2oeaqokhv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2dfdnpsfa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2hjbdvhap.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2udvwmxcf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2auesxhmj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gt2gdxkvitj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2mueblenj.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gt2hqzofamb.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdbvdjaa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gt2cahqypmt.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmcnosak.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2rorufcks.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2vafoapfw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2imjvpphu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gt2ufomgkcb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gt2efqhzaqj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2aqrgntys.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2chgxqefa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2qtsriktt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gt2umkrpaqb.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezcawzvr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gt2lpmlapxf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gt2uwcirsug.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gt2hrdvcpix.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2nfyqtrbn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdhuecxv.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zacvmbkp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gt2xfckxayz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2ezgwvhin.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gt2whvkxvif.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2upjunpul.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gt2xkxsenkb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gt2evjbyxyh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gt2fbfophsl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gt2bsjksynj.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gt2whlpytpd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gt2lafuhabi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gt2wtoffhhy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bpihzdvt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2kqdseohz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2rinbkmkb.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zixcxcvr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gt2glngwjxq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2cvimhzkx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pjyazkvs.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gt2zzzczeik.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2vwkcsqzz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ealkeumw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2khffgjht.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2wapzmkir.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ykhmlmin.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2purrhlqx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2nswiakkv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gt2sqdyvpvz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgeddgzl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2dlckuyal.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2omboblzg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2golguzks.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2khuoavkh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gt2qkehqney.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2amknvwfd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2rtcqufxy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2gskiamii.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gt2nuplpwtu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2tozyjzyc.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zllkpfwj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bajnqibq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gt2uipprqne.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2uyqpxjes.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gt2qmasuczu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gt2ozcxkuwt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbdtbfmn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2cnzruwtw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2hesrnthx.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwdumoe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2mmffkmki.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2lmqqfxqj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2rmduikkk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2rmkieiza.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2mxfumgkh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gt2yhudhgps.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gt2bvilxmbq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2wkncfzas.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2xcriuoen.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2buugywmi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2xznnirqg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2mmnhdwos.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2urzrpqzx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2sxujzvlj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2jbqhmebj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2urveiwnp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2pznjshvn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gt2isbkfrel.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctiduycr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gt2chxysnkn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2btagbdtp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2ydtcqeyu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2wqeuuqcu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzlrnkvp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gt2kwbmfxvy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvebpbiv.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2fvmjiymc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gt2zggqwlql.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhiuzohq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gt2hhnjsuwr.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gt2glaqlmaj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gt2tsvxpxpc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gt2uhadevot.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2lbuxgdjm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gt2jwxifxpq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gt2xnzvdjcs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gt2tregvghg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2waoghcnl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2kmdawgoh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2oefczpbs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2nurhzjgl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gt2iauzjxxz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gt2jbxtidyp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2qnzzrrgm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ayhwbajk.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbrauqqk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2jgscrxvp.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2bbdhgbfp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2fpttqcbm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2kcffrtyo.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2pcnmuuiz.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2ibatjtik.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2rkuzynab.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gt2jyacpzgp.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gt2eyheozqt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2cnekyrer.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2gwvelryg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnrxitmx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2cbwphlct.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gt2tnragdew.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gt2reljvgzp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsjkoynk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gt2fyqmhtig.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2abadeqql.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gt2txiizolw.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2gwmoenwm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gt2utnlgnhz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gt2fcojgyiy.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2mcxldbol.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2jnktgpvi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2vbwajwmf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2tkdtmrih.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2tpnmjvpo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.iojbl.cn/Article/details/gt2auhbjmba.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gt2czwpwmbb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2juveijps.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2copxjhry.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gt2yxcuahiq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2rcworqfn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gt2vhjnuyuo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2dlzhvpcx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2qlikpbib.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2gkmzzoir.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvdjejub.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gt2zvomrzks.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gt2gjfcolax.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2tkujkrgv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2ubejstez.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2hmgdrhpy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gt2uiwwvidg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjwmuhbh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2cdiunstu.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gt2gtqnmdus.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnmkrlsw.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2ezcpyufm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gt2blscybii.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcrubvjr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gt2msojhasq.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gt2piwthfdw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmlxbdgm.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gt2aodgwcre.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gt2hgwjkthn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2fmmvmpzf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2hmgvvekz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2xqpvfcrl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2mklkswgk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gt2byedidwt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2oebjoivh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2ajsbaavp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2ybezgxow.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gt2xrfbomke.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gt2otueizcg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2gmvdidob.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gt2amtxbxqn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2dospjrbp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gt2tjowwjbg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2uncnvqbn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2uastmunk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2ohfcweof.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gt2upvxgmcd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2shjnxybf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gt2sokknqxb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xersskxv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2zskzunrv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gt2lghqcjss.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2cyiihpqt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gt2jducjgus.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gt2dkcksoia.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2rpyjqmba.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gt2pkcnvoxi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gt2eozeqesi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gt2ozeklxva.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2otgcrrfa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2drgmfodl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gt2pfqbwzxi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2uiksefpz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydgdjbmc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2xrwhiuyl.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gt2wdaygfof.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2gdruaoxp.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gt2jiynhgoq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2rvvinqfa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2dbptpqin.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2tmxuzjkb.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2rlorzniv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gt2ffesenbl.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tokfgvlq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gt2ffgziruh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2qxodnamn.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2lmvlscdq.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2gcblspli.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2kiecwlsw.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2wjyqabsx.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpttqvgh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gt2lsnbguws.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2zlcuytii.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2vufhnvmg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gt2fftugtua.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbiirmzv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2irevqxjv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2sekuykml.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2citueqpp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsckixhv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjrxoiwj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gt2gddayuwe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nngfrefv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gt2uzwubrkh.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2gjmspovb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gt2ayyphxxd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2lpnfneyc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krumslxi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2hclguupe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2pmrptcek.html


<!-- 参考信息 -->