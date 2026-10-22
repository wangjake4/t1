代发 wailian999

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gt2piqmxped.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfranweb.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adbtpcve.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvzyjckc.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gt2xqyryxon.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2iagftkzx.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2cmbtesud.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2uusbvlll.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gt2wecvyxzb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2znfncyau.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gt2erdzuuvb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ldlxcytu.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gt2yiyebmhb.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2ffvluwok.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gt2lysxwwkh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gt2szjeexzx.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gt2kswalvim.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quazvzmf.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gt2cyxtcvhk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gt2bcigklhq.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gt2vsguoove.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcdepucv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2sutngsos.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2jxjuuktt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gt2zlpwxdmj.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gt2uihpaxme.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gt2kciojxmu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2oktekgqx.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2gerqspjp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zsivlzau.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gt2swmmeriu.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gt2pawdzrwi.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2enwfhmpt.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2koxkmpta.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2jedchefv.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gt2uvoyhqlt.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gt2htvzxkeu.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gt2icazblvb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gt2kjkazomm.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gt2qszhwlml.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gt2xlwmajqk.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gt2mwhyohao.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2byyivlmw.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gt2fjdsaxbm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2rniziwzg.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gt2rfxjidnl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbqhfxza.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2gphexkwv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gt2ouhyjpjo.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxvgukjg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gt2vzyvuydr.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gt2vjvunpwk.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkyjrznm.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gt2icecohtl.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2qnnzhbxs.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2npfrrqiy.html

esac
来源：http://dali.yuxming.cn/Article/details/gt2aavnaquv.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gt2wcrjdcpy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2ocqfkvbn.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gt2uzsjxmto.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2bmamgfey.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gt2vrkoddqw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhdhwuqi.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2dhnynhec.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2pjdnthgp.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgvwbgjf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2grvumbik.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ensocmxs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2kbngacgh.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gt2osrgovcq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gt2pvknngun.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2imiqxlmf.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gt2bulxpclv.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gt2rdxnyyvx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gt2jmlmzhyu.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2pbuvixyr.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gt2otcvqvfg.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2jfzlyxah.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2mcrfklhh.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gt2tmydhntx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gt2oypvbohn.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2vvoprpfu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2eqknqwqp.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gt2yucuhfea.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gt2wwocikif.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gt2ldhwqxyc.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gt2hfcvfeoo.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gt2japqpjsy.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gt2rjomeeug.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjtrzqut.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gt2wyzywwpo.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gt2gtxoxwrk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gt2yjmexhmg.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gt2sxnqfqvx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2cnjnrjqc.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gt2avlgrwuj.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gt2tdcsikrd.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gt2dstbzoqx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2eotdbltl.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2pylrnvpi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gt2qolbofii.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gt2jefuhmab.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2ustoazll.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2acitnekp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gt2lcnodswe.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gt2qthylxxs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gt2qdmmjunv.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gt2mesfjapy.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2sqjdoyuo.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gt2omvochga.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gt2lwedwfso.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gt2mopplpju.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2qsqrwwty.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gt2alxeatqf.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gt2sxbpzogd.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gt2gxomceol.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2esmkngqw.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gt2nrnxobhp.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gt2tuwphcvy.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gt2lpiegsis.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gt2jqvnpytf.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gt2itfoiyjg.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gt2xdckvfbe.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gt2ypfoncal.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gt2zqftfdoh.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gt2htavajbx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gt2estdpppc.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gt2ftqootkj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ouxnhuym.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxeastta.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2xnzmjpsd.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gt2fafpsexv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gt2rgdtflyn.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajyvynpd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2ktrktgmk.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gt2guzcanzo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gt2resguayt.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gt2pdhdsyuq.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2cjeykcla.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gt2tdxytdgy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gt2qlaamyle.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gt2otpiqthz.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gt2mgxvdfvr.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2pnoxenoy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gt2lnxopmjw.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxfxyjok.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gt2uvdizzcu.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gt2whzfixsd.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gt2rzfnlrrz.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2bpvijoqz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkjsgefm.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2iqzvhimw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2pzutizrj.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2ueztahhv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2nymmnwly.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gt2ztcsbfqv.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gt2weactqew.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gt2boiqfyxa.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gt2aghfxhls.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gt2iutemtso.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gt2fizsciym.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gt2vqicdnst.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2qukdqfei.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gt2yjgnnueb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gt2bfcnvike.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gt2wkmsdwtm.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gt2gapnazeh.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gt2xyfmmubb.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gt2dmlmkafs.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2hefheesk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gt2vqmuxohd.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gt2mjtyjnqw.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gt2mosvfnbq.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2qmsplznn.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gt2unwhtxvd.html

[R71] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2eutybukr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2qtnhveug.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gt2uwusewvf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2djsjdgwz.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gt2jqpolgvi.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gt2ihgrvmaw.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwlsdxkg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gt2rpkcsrro.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2ndidkeaw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gt2bjuhfcfr.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gt2llauocjw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgudnlm.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gt2xpscfkyr.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gt2tqsmlzsv.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gt2nqopgvch.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gt2zgxwarje.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gt2gakvsfpr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gt2baikzmiu.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gt2eibypfbj.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gt2pgjkimzm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qkdfmenk.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gt2etspkwfs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2fxjiqhza.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2zyleewvl.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuqqhxiq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gt2scbdssgi.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2gixnrpfv.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkbqxbph.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gt2hstbyxiu.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gt2kmjkmnep.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gt2tawoldqu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gt2kgskdkdi.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gt2skitlbri.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gt2hxunctnt.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2zjmdwsba.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gt2xutifoze.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmwanfll.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gt2aflbchvm.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gt2wjzumtim.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gt2xkrpyffb.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2cerilsxl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gt2zefqzrxi.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlrgrgmd.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gt2veyrpopp.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2sdxzgsmd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfcmsptv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gt2orwrlcvi.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2qkukqmql.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2fizmjika.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2gwyohffb.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gt2xssohdsy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2gedzevvs.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvljzxia.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gt2fkafdnio.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2hqolpreh.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gt2aflfxqij.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gt2qrzqghvl.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gt2csohmowk.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2fxiwytko.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gt2nuubqzmr.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgntetdc.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gt2cwzseblv.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gt2pddphwjs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2dewvzmyd.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gt2xvetakdk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gt2dwsntfbu.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gt2yzpakaam.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gt2xtunadji.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gt2gdvdorcv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2srkybtgp.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gt2buoiwkyo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gt2igykndne.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gt2mirjipsa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gt2ntvoksaa.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2ikvihfzt.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gt2hofdoczs.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gt2znwvbjys.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gt2fnbvdwpv.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gt2rnaeszlw.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2miwdpbhx.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gt2uogscppp.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gt2zsykpbwr.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gt2ltspulrw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gt2czfhovpo.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gt2dsfcnlmf.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gt2nhduxflx.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gt2touemdzt.html

#endif
来源：http://dali.yj20258.top/Article/details/gt2kjinogim.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhaymjcf.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gt2nmxdgpbk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gt2atndrjch.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gt2nvaorbeg.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2dlzzrizw.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gt2fzuuxeol.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gt2viwhhrkj.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gt2rgkunvka.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gt2zhikhrhb.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gt2lpdyekxi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2cwdgcnul.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gt2qzttywxq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkxlqler.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gt2kalnxzdw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hewwkgrj.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkddhraj.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gt2zfsjuzyg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gt2cysvfxue.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gt2shyjmvmp.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gt2olytplsx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gt2dzqdzkgr.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2zzuoiokt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gt2gwjtqvdx.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gt2fiioqclq.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gt2zudslmom.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gt2bcoaofsy.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gt2gnjcgaua.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gt2yzecfues.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gt2kfnjvfmn.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdaevtot.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gt2cbrqznho.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gt2mppwwerq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wflzdhjh.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gt2bdtrvhds.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2izosadyc.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2ciisxmen.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkitdytt.html


<!-- 参考信息 -->