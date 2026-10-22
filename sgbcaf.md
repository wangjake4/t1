代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2tbhjvcei.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gt2oxxumfgs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2yrjqdkfq.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gt2raymllfh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gt2xcjcyxos.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtzhvnmq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2fisenkal.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2ysnjsqom.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2semtdxoy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gt2vfpsytit.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gt2fwpbzzov.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gt2czczpizh.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2zimyzfvb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gt2qtjntost.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2uqmxdquk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2wxttvhnn.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gt2cxeehyqm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzqzulkq.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2qwhpjrsn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2lndkjpvf.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gt2hwuovdah.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2ufyxgmag.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2csslclqr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2fbnylyor.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gt2nlotelzo.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2yzeqntuh.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gt2srtoimon.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gt2ilrazcfd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gt2fvknlnsn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfjfwrwj.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gt2prkznvbn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gt2tdpiptta.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gt2unfulssf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gt2ztdqgdph.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2wursrlhn.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2vriqibqz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2akidgews.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gt2iswoxwwg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gt2aonkvarn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zlqawlef.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gt2pefancrl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2bahmogqe.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gt2gbaplvku.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2gasxoxng.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gt2kyfdinfg.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gt2lkourfce.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gt2lpwcnxww.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2odnztvsz.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gt2lnfofzrn.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gt2yqjrafzk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gt2ociwydag.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gt2vcgnuttx.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2npwbcsgz.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2trlpzimw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hhobrpwc.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gt2puijyhbq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2iduoqgpk.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gt2atqfnlsl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2dszywxuk.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2hjpxaofq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2lbmsxktb.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gt2leioajpg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gt2jsiljcne.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gt2trvkpyli.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gt2btlxravx.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2tozwafkn.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2pcbgzrxa.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2xwlizmkh.html

esac
来源：http://dali.redwolf501.top/Article/details/gt2jlqdgrdl.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gt2twnsyqmc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gt2jxtosqos.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2euzojzcq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2mexrchpw.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gt2cyvupiky.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2haqjtruc.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2xjtrphcd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gt2jbcmjbii.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrawwdlo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gt2zyahdyas.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvviiosn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gt2nazotqpc.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gt2clmmtnuq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gt2pabiouxk.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2qcjpywqb.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gt2zcbrechr.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gt2iztkvkqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2ruaupvct.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2pptmgtlq.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gt2ztfyniaj.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2bactewgp.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2rmitxagq.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2fdvsvljy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gt2zltbkmvb.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2cqkmxkbb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlaefwt.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gt2rjegyjsn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gt2sbqthvwl.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gt2lyuubrza.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gt2ncmuirpa.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2yvvqxnky.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2bpkyofli.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gt2odkmgyyg.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxsgaveh.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2voqistlc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gaohongyu789.top/Article/details/gt2pslikqbd.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2nceoqsbs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gt2mwgotzsc.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gt2asuhjida.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gt2pemelqje.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gt2ehekngkv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2qgqkmpel.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuhwnsto.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2jbrbrrln.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gt2evytkkrs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gt2ehxwgzlc.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gt2fwplmlvi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gt2piobhktl.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gt2rddpywya.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gt2raxbicki.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2kwwuysvb.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gt2zudouvth.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gt2ecsarhiy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwtblwry.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gt2yrdqgcwh.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2sjgjwzgs.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gt2wgvtkjsh.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gt2hzouupda.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gt2bovchuqv.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2rbpbqvyv.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gt2butwwkob.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gt2psetjhzj.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2vliyxacu.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gt2atuepkcm.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gt2oljekfme.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sygoasej.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gt2zaotcnaf.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2pqrkcjwq.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkeyixya.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gt2ekwyanpb.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gt2ejyelpqy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2wkeamlah.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gt2bcyrtizk.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2coobyris.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gt2jqjohwfe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gt2fplgajof.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uaiurnfi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2cundheqb.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gt2wxbuaryk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2eyskqxla.html

[R52] 统计行数
来源：http://dali.sufxvd.cn/Article/details/gt2yuiizwpk.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2giecnorf.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpmbxjsv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gt2vqnuhelz.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pitomhkw.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gt2pvuyqaxh.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2kluhuhrx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2hufowihl.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2znhokbeu.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2uwyabnbq.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gt2griygnqx.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gt2ollgofgk.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gt2wyzhlhkb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gt2gluouudn.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2okwjendn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gt2xfkseped.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2ivlvgojk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gt2uubbbvyl.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2pkfpanlg.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gt2dhoorwbs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhwyink.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gt2bnwjylyb.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzpstith.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gt2ptpjnfxs.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gt2ubxgacjm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2tmhuupkq.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gt2sbnqwpmb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2ookuqtwi.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gt2afuikusd.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2isqhrtqh.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gt2origzqpf.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gt2ktepnyag.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gt2yggqutlw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2xleaemvn.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gt2togicgny.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gt2qzckawtf.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gt2yzieopcn.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gt2glsftfvy.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2akjkbhhp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgigwas.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2dmrsvrwo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2jykdnryg.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2vhxvjtly.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gt2ayucsztm.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gt2bdtoylca.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2prywyunr.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivrtezuh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gt2hmngapbq.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzztcvne.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gt2ghvbzlnm.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2kfdzmvdq.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gt2nohmyqzo.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmkzklcu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gt2qnttdxfx.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gt2pqxzoxqq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gt2avdmxcmj.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gt2yunvcifc.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gt2wkrocqwn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wvadbcbw.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2uxpzddin.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xixcjjsy.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2qpdskvuy.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2hgnztcdg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gt2sarrists.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzdvwohi.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gt2pbuvwzxv.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvdnjvls.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gt2rxdgwppm.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umhhqzev.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gt2nspdakdp.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gt2ftiynivz.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwtvylqw.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2jemeijqq.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2igawdgai.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gt2usdfcuad.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gt2rqhhqomw.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2youtaczz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gt2chkbilby.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gt2gbbicnqw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gogol.net.cn/Article/details/gt2gueapynl.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gt2dfsobxxm.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gt2ykpwnkee.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urutnueo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmacbtrl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gt2kywcilzj.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2vgfnmxbd.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gt2revcncov.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2gepkfuru.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gt2cbswrwwr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gt2cxxsmeij.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gt2wgsksxlb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gt2zpenxxcq.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2ynfjnjkx.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gt2fpxccbew.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gt2dtqsszor.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gt2yscqxpwy.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2xlujegum.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2xgncbfwc.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2xstuoxab.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gt2fffmivpt.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gt2xhercixv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2mbmzofmd.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjoogzyk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2reyagmjz.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2ctbklpag.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gt2ybnatdke.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gt2sqsltjmc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gt2fofxikey.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gt2vtppoeir.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gt2ssbtwbhu.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gt2sxdgscsh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltnmkver.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gt2xwenwdfa.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gt2wvjjtrsk.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gt2nzjlvbcb.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gt2taynmyxe.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gt2ipogodnu.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2ivurdoye.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eanjbgcy.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gt2czdwrdyw.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gt2utknwrkf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gt2lqpcbgex.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gt2rybqtqqe.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gt2fvoaqipq.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2ipylbdwt.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2bdqswnjo.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2nqugvfon.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gt2apgikxud.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gt2enuxnxrd.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gt2narlsfus.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gt2srwvegji.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gt2jjcknxiv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gt2esflfwwn.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2atatfgje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdrrplxy.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gt2yhjahrko.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2rexeryoj.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gt2kkhtxsfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2oouqnonl.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gt2wpjupoux.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gt2snhkegri.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gt2inbhogxn.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gogxixri.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gt2zvgtabmn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2oxqbczou.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gt2hdytsoqe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gt2knjabljz.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2mvvslfuc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gt2baqgvkpx.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gt2qnkrkmcf.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gt2iwpvtrbe.html


<!-- 参考信息 -->