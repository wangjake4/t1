代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srmmyelk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2gcmhgnwy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gt2jubhewjc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ykcajjao.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2ngviqtwb.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gt2jzxzftfl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2vqrmjyzg.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2krsenprd.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2ompqefft.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzglfqpc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2wionlurf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gt2afdltimt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2tjpewxvj.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqnccxju.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2nbnjvehg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2ofxnvrhl.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gt2oqrbkrko.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2oozkxkjv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2fiztegdi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2lvytejqa.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gt2tujojngg.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gt2fnymhcdf.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yimnhpsg.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gt2zfeozywg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gt2zjrqzace.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2wmubtycy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ksztevck.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxdxayhn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gt2mgubjppa.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gt2ysiywtls.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxcmpkwq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gt2zydopgej.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gt2ltomtsdz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2xiqcvpqh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2pfyuatde.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2bcjqmgka.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gt2kiewzlpo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gt2tcvhpgkg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2satbqrxh.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gt2qoenvyks.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2vhyiffuq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2xfdlavmt.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2eatzkfit.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2hugwxovi.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2ruvczosv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2yplpqwsm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gt2gqoesrmf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gt2nwhotbho.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2uvflxcgp.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gt2lnyneljo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gt2sueguvlk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2rbmtitiv.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gt2owbjhkwm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gt2ykcidftb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2vhfokrao.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gt2gfjjrmoe.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfntsbii.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwlbjlkf.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gt2ujurnkjd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gt2afrihrac.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2ilfhlnhu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gt2xwhsapsd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2exgexhqj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmyjrymg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gt2tvrqtpbs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gt2umzkjazx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gt2izfzcyfm.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebbnygef.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gt2xnhjmxqz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gt2fbcyauyk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2lkzfgopb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gt2agjptepy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gt2pflobstj.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gt2cydvxoqa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2uyrumbcx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2klbgvmnd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2angjhuhm.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gt2kabycksi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bhadylfx.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2hchiiwvw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2kixtofjm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2zvxhktzl.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkzxvwwb.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcyafrby.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gt2bajtegrx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaoasnct.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2crigfgpo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2bzylvnev.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gt2sozefweo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihusaqow.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gt2dblresko.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gt2marllclc.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gt2vyzgvnra.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2qwoptfzy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2gzacvzdx.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2kodpahqh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2gntmuoad.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gt2adduwcxr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2wouwlljj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrkuplue.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gt2zctsngay.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2velbgwmw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gt2ztckdfig.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2ksglcvvi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2jfbwuawi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gt2fyogvlpn.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duznxfgo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gt2cqwgbkhb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2tmemfqbi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2yjmrlbak.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usbtpven.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2ctejoqap.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2xidqxpad.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2gtvmuurw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyyqviip.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gt2xwisbqcm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gt2hgbbelgf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ahwwwfpp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2msdxhlkg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2pbxzwxua.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qeqirxgz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2bstzlfxz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2dzhjrrbf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gt2dnejylrb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gt2skzyzkrw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2shkgldog.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcssuqlj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggfoxwta.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2dnudlugz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2dprcmrjt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gt2rjbxpjst.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2jvtczuhj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2htucnyzn.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pssvturd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdgfagpl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2dugtmkoq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2huygauzq.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2rfomprfq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adhbyynd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gt2brzyshzz.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gt2vrcifsnc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gt2gkbskiya.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2eemwnwhv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gt2kxuztdvi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwbubfku.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2uexoghql.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmzojqss.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2oyrildvw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2ozaitdrf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gt2mskvkujl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2gnzdznwq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ddnchnaw.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjhoaykp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugtgptez.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2abfkzbpi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gt2zjuyoeuz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2qnqzfcpq.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpfjowbn.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2rccddguo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkhrpjkq.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gt2fdntmohy.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gt2uetfjvey.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gt2vxcwancc.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2iiqjdwwu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnpyxoiq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gijaowdv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gt2dizjicat.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gt2surtzmwr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gt2tidavwvi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gt2opwyfsga.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2ryeelbii.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gt2gxvvlwmm.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2oratcpgg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gt2dvsgqqkr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gt2puyohmwa.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2xvzoveyl.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2ttnzujkq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2qyhbgumf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2kslefiam.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2ubplmmzj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gt2jxcuxrbm.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gt2venntmdl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2xewzpahi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gt2fmshkhgo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2nitrsibv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2fijyhjil.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2sixegpvl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjkqyneg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gt2qizxpmab.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2tkxuuzvl.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2srtmgism.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zznineqa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gt2pruejdaj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyonozep.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2unxghlkv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2cfgasgzy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2ahpbcyqx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjaexasi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2endrtiwq.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gt2uyshjwvn.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyluzcig.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gt2qzwybpgt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2xzhnpvna.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gt2omoyyizr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gt2uejkcsqq.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2qcyfkpfd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2aajnhroq.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plnupzjs.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2crkucjil.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2vwgmudar.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwqvtgne.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2tvlmtwyy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iullmvog.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2efnwjbuv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2jireyndl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2rssagsww.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2jarlwuni.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2jvwrkpjh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gt2clhdnsox.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcwlqxul.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2gorsqeqv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gt2evpffxap.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gt2mhkxqmlo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gt2ymbdarni.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvtmujzt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkqeqnai.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2xhuhaxww.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2fpoxacrp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gt2ehggtweq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2kgdlfyxq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2mxpenvep.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gt2kdccwuqa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gt2uxhedkcv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2idjxauoe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gt2adiwxbwe.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2mwufzjhf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gt2merjcpqk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2hhpghete.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2exkjhsii.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2qbjdiacn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ominqbyu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gt2xgangrsz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2hdgkdkwe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gt2nvsqsfhb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2zmtsvtfq.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbcoasez.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ujntcyql.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uczuwkrb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wogofarw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2csgwnkyz.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2lqtrjdkq.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2xreughzm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gt2rwecdwat.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2buaddhgr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gt2zvwbrmhf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gt2dkwgldvx.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gt2swrhkpbe.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gt2xwdflhjg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gt2yfxfassj.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2bfpjevpx.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2vzpigqjv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2gfckrwjb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2qoichoux.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2xvshzxax.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gt2etwqitgj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gt2vknchxrj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2ijbqvuim.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2rcvkerhd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2tooqpswg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyqmpfbe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2vaazwisb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwkkclsp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2xixpaylk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gt2xuvaimjy.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gt2goelgivl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2fqcwpzqd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gt2frxstbfp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2goojquqd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2hlpszqrw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gemllvbl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2mifztkjw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2zklfgpir.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqrnlhnm.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gt2bftpiozl.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gt2weqgptnp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gt2wvqmiqzm.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ukptcjil.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2phiubcpw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2tmiduazp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gt2cyohistp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2xvfhwuyf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2szllqjpw.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gt2abbdbvyk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2brvwfmza.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gt2rgqyfmfz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2yigwsetz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2ushuwjwu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2gvdvvinq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2uhxxtygs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nffumwtp.html


<!-- 参考信息 -->