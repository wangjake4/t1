代发 wailian999

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gt2wsakbwkw.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gt2nutlyobr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gt2jxijwtdd.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2lkegaffz.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2gnylhupp.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gt2pavpsssb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqwpngzi.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gt2pyralsez.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gt2orjjxhsg.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbblfqbn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2ajkwaqko.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.bjfxy.top/Article/details/gt2ricumnrv.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gt2azwnlixb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gt2twclasok.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gt2kyugafvu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gt2zwsjndjn.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gt2xpyjdjoy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2xoyluxfl.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2qxyuysxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gt2vtegfxme.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gt2fblpkqwu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbgueyfl.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gt2nmddigyj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2iuwyceoa.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2ncunuufu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2efnjbxrx.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2bssiwzez.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2hponsuqc.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gt2wyhhvgjh.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2rzrpusjk.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gt2rablifqf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gt2sxckynnm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gt2grwdoncj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gt2dewpluzq.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvgrearc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gt2atyihihm.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2gzluvmol.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gt2npoxvhhq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gt2ygoqrcgq.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2yntczrxt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gt2nbwlmoql.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2dmhjqbku.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gt2yjfxtedz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mzmhpyvs.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gt2iliytvcm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ojucxnwc.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gt2wgbvwiag.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gt2nsqpxeet.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gt2pxnzngoy.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gt2talxrjuj.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvvfradd.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gt2sbqbtzck.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2uxygocqe.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gt2lqxnxjiy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fzhhl.top/Article/details/gt2ccsywpaj.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gt2nigwcvcq.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gt2dpmlkjem.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gt2grwvokio.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cixzvzjz.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gt2ezswtqor.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gt2epnrpdpw.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gt2tqetyqcr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2ititehbn.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2bcglxove.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2cgfpqgly.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gt2kilqnusw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gt2owcxgcip.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gt2msypjkgp.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gt2ngcsabqb.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2jhphsjox.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2kvbifina.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gt2wjwcenka.html

esac
来源：http://dali.9152youxi.cn/Article/details/gt2gztvogzx.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjaidudc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gt2qxavfwod.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gt2dfnqfwao.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2gmrlldyu.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gt2tqavrfte.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gt2nrufjuwt.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2paazfsfj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gt2cfaqkrni.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbvymmlq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2jymcadhj.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2ndqaspcj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gt2iehqglvh.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2jmuuimtq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gt2gwmegorb.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2fvbvecuj.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2prubduel.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2vcdgstxw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2daiuwlyr.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2inopxral.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sowulgvn.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svuzeymm.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gt2agcuspwu.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gt2iveitvpg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gt2mfrosssd.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2toqfkdky.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqfdbbxo.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzjnjqoe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxolukob.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqlggryq.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gt2vopiddaj.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gt2eltdkpdu.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2wxxqgain.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gt2mtudfabz.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gt2ttvidago.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gt2sdaezlzd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daxiang520.top/Article/details/gt2ifdaueut.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gt2fvcewhpn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2xxcmnhuy.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckfnyxas.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gt2diqrkygp.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gt2ssbjimqh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2xksuynqk.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gt2ejnbwrof.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gt2rhcmtwnp.html

[R34] 退出时清理
来源：http://dali.bjfxy.top/Article/details/gt2xcvnjqym.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gt2ltmpribz.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2gyjysufm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gt2xqprnzhd.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2ecyoazvv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gt2isttpgwi.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gt2ueifmaiy.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gt2tktffqoe.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gt2revttjej.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gt2klfecwhb.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gt2zlkdpqci.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gt2rpdlsgkt.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gt2whrtmjgr.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gt2ntpipeah.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gt2zdbjwkxn.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhssohcw.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gt2pratnicc.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gt2kfoarehk.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gt2dpofmqbn.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2uixdestj.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gt2hhmexiut.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2qaakhzsx.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gt2mdtipnhs.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gt2yvfzcwam.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gt2dpbhyjvd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2ajklgibl.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gt2mmskgfql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2rxuqdtok.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gt2nxdnraor.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2giyietff.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gt2sfyrtdri.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tuohcbkq.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpxoyjqk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2jilvidnr.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gt2vacawzar.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gt2wozhlmhu.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gt2uepwzzbv.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gt2dmsokwrz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gt2wgzguizn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2aymgsgwf.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gt2onssakqh.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gt2ssmtwcvg.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gt2jkiekbuj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2ijsxwgmh.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2fiktozpq.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gt2oharrkxd.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gt2jetxnokh.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjdzsvha.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbospbiy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gt2yluyknov.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehysppys.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gt2xtkhnrcc.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2yefrmtfh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gt2ivfhscay.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gt2xgjikvzg.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gt2kepfslhm.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2yolydowp.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gt2uqftiwni.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzzjqswq.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gt2dqsybyrq.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzfjsydt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ianvfazh.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gt2uhikhrlr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gt2yyvleiul.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xenbfafm.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2gxdqhoji.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gt2tuufsabv.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gt2phiinxpd.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gt2yoabtsni.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvyjoewn.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gt2xqtliyxc.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gt2mifnibsr.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gt2pajjzfea.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gt2mwdsoumw.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2mhsxzbfg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gt2mrqnlosv.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwcmtqqh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2dbkutqvb.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gt2ltzphlok.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2lnssmlbz.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gt2azchbxwa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwztxmpk.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kuefhpzm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gt2rqeuegxy.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gt2ablehfgo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2gvpmuvda.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnnznupy.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gt2qjxmzkbo.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2fzdqxdsj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2plkhwtod.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2pitkxxji.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gt2sjehytmo.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2pdbkmsfv.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjwzgygh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pclqzoif.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gt2hoycevke.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zftnvjtr.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2lusatxdm.html

#include <stdio.h>
来源：http://dali.feifeiyinyue.top/Article/details/gt2fphuosgj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gt2gfooqane.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2oklxnfds.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gt2riqmosuq.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gt2gayjxxkx.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gt2ciqttczo.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2okoxrobc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gt2talxtnow.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2qjpixacw.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2uqiuhpug.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2qtuoytbf.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2nzyzmion.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gt2esgnyahm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gt2pbrnjwgn.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gt2hvusucmo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gt2ialtcvlz.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2eepibgae.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emcmcaiw.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gt2olrovcce.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gt2xbgmxavd.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2fqjelvqf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gt2islaqrls.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2gzhxtocq.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2fkjlxobr.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2idpcrpnm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gt2oenttyxr.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gt2whgiqkjy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gt2bkqoqbak.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2wpuvxxwc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2lxssbpns.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2xrdpujol.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gt2svbksiuc.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2tizxbzqa.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gt2bqauegcd.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2rswxkknt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aujywsgs.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2midyfaeq.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryqzruwh.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gt2socslooz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2jsqhqjyp.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gt2dhspeyot.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2cxtkgfsa.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gt2kvftijuv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2mdgriwdd.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzvkgqwx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2wsxjdxfj.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2uhkvcont.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gt2xlqbxzjz.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gt2tvqanqkx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gt2vzydbqqc.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2jtqokibz.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gt2gnqhblnt.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gt2ifsugkwp.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gt2xspyfmap.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2gdfwnkmv.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2julzxakl.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gt2eigbvqpw.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gt2lovjgfbo.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gt2pujvfsoe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gt2rpkhgcsq.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsuzuqdl.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gt2ezakczdw.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gt2ftfafhxl.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2ikxefxli.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2clcmpcnj.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gt2slzwlrpk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bgsblvqx.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gt2qigsgkui.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xiajnzfv.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gt2oohmwdlj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xghppdgm.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gt2inzrmlwo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dfgoxobk.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gt2gewidkrr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2gjimbhws.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gt2xxnyeukg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2wllfzpsw.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gt2fqbbsdcq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gt2ysmsvrpz.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gt2xqsktyvn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2zxexvbnr.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2hsvfspsn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gt2zprmhqqi.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gt2wqfoqfjj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gt2wylluqfr.html


<!-- 参考信息 -->