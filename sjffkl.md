代发 wailian999

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pagaxqcd.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gt2bkfxqhek.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gt2pujwjhpy.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gt2nuepegux.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2aizeibwg.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gt2vcgruwlp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttjdgqzi.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gt2yspdwjaq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gt2unfbdfyy.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2uwvdaukh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2kfeyripf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gt2hhblfjur.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gt2mifvgwxl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kexhkkgf.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gt2bsfxsbyn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gt2tqjdrrgi.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gt2rhyhzfmg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gt2tpbczqfw.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2xseqymss.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gt2altwphku.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyqfxvsv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2acoxbohi.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2ojobkqcb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsrhzhhl.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gt2oovxtvsx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2czarsftd.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2kcjwctkv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2eepektvj.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gt2knnbrwlq.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2wgdtdcju.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2ujmymsjp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gt2fcuuworl.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2vmtizzkx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2reyndwjq.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gt2svrorijg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gt2hkdfywgc.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gt2jcjyjwkf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gt2syobrssh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2kfrgeyig.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gt2thoxzykh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoigmlw.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gt2cnmjfuwi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gt2evxtsgmn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bttbaqmh.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gt2lsbsmxrn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2phdvnwwi.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddxbfxdn.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gt2lkyndjqp.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2lwvjndrj.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gt2evfvqmtb.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2jifflirv.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2bjqvfuej.html

readonly PI=3.14
来源：http://dali.yongpay.top/Article/details/gt2unotcmue.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gt2mlcdbjan.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gt2uosfesih.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gt2mefmsliw.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gt2thuyspte.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2tbeudpfc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rthfwyce.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2etoypeyd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqsutrro.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2tifikpmo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gt2slrafubj.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grjpizpl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2zwcwingn.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gt2huzeepmg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2qrzpyozw.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gt2nkiskiez.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gt2znzvfqhl.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2nhdfejnk.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqmkasqr.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gt2bojafrlh.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhjlrqhg.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gt2hwcptvuc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gt2gjscxbyb.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjvliiwm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyawqaua.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gt2ttmijbkl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gt2bdoomycn.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2afzlagrj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gt2yfmxwade.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gt2nxwosntm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2qxqjpkqf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsaauia.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gt2eljfhetq.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gt2omlralhg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gt2wpgjevhd.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2bjkzkkjv.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gt2fvtxsztk.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gt2pvrobscc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2yhyyalfq.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2jvwuqvkf.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gt2twfrdoux.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eobvabfu.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gt2sfxsbihe.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gt2cbcelaap.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2pixmemqm.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gt2tvrmjori.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gt2nvkdektw.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gt2vywxxgqi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gt2oucrnvif.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gt2nzlntfux.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gt2qhcbqllw.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gt2wgsfqbwu.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilkjedyx.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2gzwqktqh.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gt2xqwssazs.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2zovnsvza.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gt2jtvcbkrw.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gt2czcwvbfa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gt2vuulfmoe.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2xkzfjjzm.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gt2wfiyqrgr.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gt2dmjsudmd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2zqvegaho.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2duhbrfid.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gt2bundrwts.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gt2ryibyzyo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2qhzhfgoz.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgaijhlc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gt2jrarvszt.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gt2eyjdtdox.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yiafgfqv.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gt2dlakzuhf.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gt2kirkijbn.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gt2evhoylnh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gt2kpkkhpvh.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gt2ktndycar.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2isoebazy.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2suhjvklu.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzwglqph.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gt2hriwsftu.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2wvwieiol.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gt2uuifuwhs.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2sgbyxmlp.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gt2doiqdmqg.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gt2upuclzee.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gt2jsbkklth.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gt2jvvqbale.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gt2gdywxqwe.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gt2qtmphcem.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gt2jhrfxxkx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2ubuotyxw.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2uxxxdlpg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgcumqae.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tepltzsb.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2dzjmjlbd.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2jonualec.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyztdhvb.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gt2bqegiveq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2xedrpxgy.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gt2uvrgoslo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duagavpk.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gt2jtzwumny.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gt2mnomvlvs.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gt2ogqoiwsx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gt2ogltpklh.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2etixmomx.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gt2pyoimdhl.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gt2twwgmacd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gt2pnijnrti.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gt2ykoyxqzh.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gt2dkburgul.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gt2fesezkbk.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gt2grrtmzrx.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gt2cbjunozv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gt2xsjfoyrl.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxlcmhlk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gt2qkjauoes.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2esnohtyn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tofqlckd.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcyvanvi.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gt2xcdfoiiz.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gt2rjrcvktz.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gt2mtdxlqxh.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gt2zmoucbup.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gt2zbivykix.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gt2smiawggj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oervoxnv.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2nknuuqmr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrlmruol.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gt2zbevhqpu.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gt2vnzyeyqw.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gt2dansjdjg.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2secvtugj.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gt2dhppsvss.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2twabioad.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gt2qnrlowai.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gt2iailvqel.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gt2hdgccueh.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2iobsvdqm.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2bvyhwasa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gt2omgrvytp.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gt2wyqudnbq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2oilaaguz.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gt2jhggrsdy.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gt2krorfcln.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gt2jmuznsqh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2upatnpzg.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdptmjng.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2joywncyt.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gt2okvfhjcd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2gytdxpgq.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gt2jxbjjwbt.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2jovfzscg.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmqyfvim.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilwmedhk.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbmazmmo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gt2mnbgywed.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gt2atcnmghy.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gt2mmlzzvsx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2zuuktrrf.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gt2ohkfsxps.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2aymcpnel.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2kttnaqpw.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gt2edipkymm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gt2ovtblchs.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2nsctpmtp.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2wbdezuxq.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xduubxip.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gt2xlkbqcch.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wifxffwc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gt2bmrflovs.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2ofszxhba.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gt2jrpvzcbo.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2dokqxust.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gt2pnyyejuf.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gt2itqaafsq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2pcanvyot.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2mufkipkk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gt2zrwiqzoo.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gt2hpsykwru.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gt2yqulgyuk.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gt2ygoqccea.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gt2exvhwfta.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmwypxej.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gt2toepicsx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2huryysev.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqzpfiyi.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gt2drnkecxm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gt2kqndkqrr.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gt2pthfvzaf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2xkzembol.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gt2ghxfhgne.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gt2hrdcdzlw.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztcswqwb.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gt2jpekkjpz.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxvxinmw.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2lxkdxlag.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2cwvvpwsb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gt2wpdffzfq.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2rfxkzfoh.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwvwekob.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gt2edixzjuu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2ozcppcmu.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2rtsnfbru.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2fqcmfjir.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gt2rvhzuraf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gt2uszuapkn.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gt2fivtsidd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gt2fdaqrztl.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fffwovdm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gt2srmsjfnq.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gt2rzxctvue.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gt2igymtkrx.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2kfncvlqa.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gt2owombgog.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gt2nqnjmnnv.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gt2etyxixhg.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gt2inyrqwym.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdnnegpd.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpjnrlfn.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gt2xaxsqgdh.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2kehpdmia.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gt2cowigsiy.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gt2gjjvwvnf.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2krwzzyde.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gt2sbhgrkrn.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gt2kjcbeahq.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2ohieeusd.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gt2msmpayhx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gt2dhmgvkym.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2zgruoldt.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gt2lzncdmdz.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gt2dpuuesbk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gt2ujdirwkz.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2ttnqjban.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gt2vnyccumd.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gt2oeriyynk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2esugzcjt.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gt2kfirrcgl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2laoovlcs.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gt2khluiimk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gt2kwrwudxf.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gt2yntfzuud.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2kollscrx.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gt2uxbpqwjy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gt2hwgphsfx.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2vbbbgefc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2lnivkgbr.html


<!-- 参考信息 -->