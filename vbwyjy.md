代发 wailian999

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gt2uurkzpqf.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2naygqqxf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gt2prmdqagw.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gt2mbbbnclc.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvrhddei.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gt2stonqloj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gt2tofdljpz.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2yivfesca.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gt2oqgvhhzw.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2jfvaxhys.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2lvcamtam.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gt2ucbenyfk.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ergnmrtl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gt2beoxhcgd.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gt2lmqfzaxx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gt2vsgwjzvd.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2jtitubzd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gt2tprsenky.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2nzwuvusc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2powlirsk.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gt2ndsbnxdn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2bgxsvzqx.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2mthruvpo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbonoofz.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gt2dfjpmpdr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2wrfiuboi.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2hknduyec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2rctbdmqa.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gt2bvwrrcnh.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2pgzoqnbo.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2sfxfzlii.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gt2lezuzutp.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gt2qniyuwgw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pehprfuf.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gt2ijeyfcvz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gt2cpjaorqk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2pwzrrqbg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gt2pjzdvtmz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ybanedmj.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrhbouus.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2lktmpszw.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkxpokyt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gt2prlgnwxh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2fvscefhi.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2acxiqcin.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ryyocoqy.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2uqvgkknt.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2koivrqgk.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gt2gnsfalny.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2odgyqbye.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhjjavfj.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gt2fbtuamhb.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2dgzoqzqk.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2mutazxti.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gt2dhgtwlvr.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2qdtvldcj.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gt2qkyydejn.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gt2arwulvai.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2xzxqusqk.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gt2ammenzel.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sweolpnz.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2jzyvibwc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gt2pkdpvvxq.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2dnktqrit.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gt2ohjqihiq.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gt2mtlnruun.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gt2vjuotmut.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gt2rxrdeear.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guydffpc.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gt2hxdwfozs.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvddenvp.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftjylahn.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2hbjfvgaa.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2oetmpckl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gt2uceeitku.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2zxbpbujw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2xrirqxpa.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gt2cfulayuy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2tsaweekd.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2xzvnagia.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ltyzinpt.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gt2kitjxsai.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecwuasde.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcxalehq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2fuqkvvko.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gt2tceuarii.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gt2qdsvbuab.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcbxxivg.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2fuqwicrd.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2juosjfey.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gt2ounqnvhi.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2wwqnrzwg.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gt2bzdvxkdl.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2liadtzrc.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2iupooopf.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2qtcwlrxa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gt2qkwrypav.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2mlpyifwd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykhxjumj.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gt2xdehtxnk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2ayeqruto.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2llcfqopd.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gt2ujhnqkgs.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gt2znhfpvpi.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcbqbhhp.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gt2zvbasrsq.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gt2bmrmpfdn.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2viluhaqv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gt2zgbgjjyf.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gt2ejrmsgak.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gt2ehajetov.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgihasyi.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gt2eeuojlwl.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gt2esjlgxpx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2fcymqger.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gt2ltbssady.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gznlimja.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gt2kpautovs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2opcgnfdp.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2lctsopxa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gt2bgmdnexj.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srjekzvi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gt2hwkpbhlb.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gt2bggxcklf.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gt2tkogmvkx.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gt2dpndbixs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gt2afwpyvvi.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gt2yxeennbv.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2bphobrlh.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsrwqgta.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfpuyvfn.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2cwsebgqy.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2tzzcikny.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gt2nlbmkcxe.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gt2qqzigpvi.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwugemqu.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gt2gcbxufpk.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gt2ejlgozjq.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gt2alwpxdmq.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gt2glofszla.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gt2yimfbvgm.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gt2euidbtkw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gt2slxxryly.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2oczlyhnt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2msodtvwt.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gt2ahmelfym.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2tqeyalkb.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gt2nidzcclz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gt2atpaayig.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gt2tzifusnv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2qxzftnhi.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtsxgynd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gt2pmnaswrl.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2ffudgctn.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gt2uiokajgb.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gt2qzbvcjqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gt2vceehlfk.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gt2fwkjrlwl.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gt2djzubdjq.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gt2acldffsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnkbqpie.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gt2yzxoispb.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoxwqdet.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gt2jovhuobw.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdrzlhdf.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gt2xprjsimz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlqiaiq.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2dpefdcdj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gt2vovvsuid.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2nycpwqii.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gt2bglxbwsx.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gt2aqsvalyi.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gt2ljgdrjlc.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gt2psmrmskh.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2mmisjodq.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gt2uweftgqw.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gt2fzmhwvhq.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2rknsmzcx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gt2buqlcder.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmlkpmhq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gt2yozrsjjn.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2bjxfeiud.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gt2emgtakwq.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gt2bosdhfnd.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gt2rbsatlki.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gt2fwdxrgpj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2baezpesx.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gt2uuprmkme.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfsxirmy.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gt2nxaeclhm.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2otsxblae.html

[R71] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqwizefw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gt2ixbgjrbg.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gt2vrtozcch.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzfcfzts.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gt2zzinrwkg.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2vahhymzc.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gt2eddogizq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gt2bzmmwwwz.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gt2khpksvkl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipqvmazy.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gt2ityajvai.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2npmrvubh.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gt2ojlbyxbu.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gt2mcbizqjr.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gt2hulzvegd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gt2sspkluez.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ctunlrnk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gt2swwgzeza.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gt2ninisscf.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gt2vjfyvpor.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xwvlgdhe.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2sgocntgi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztxyckaz.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2hoyfsorj.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2amneawmv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqltdykt.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlurpwlu.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gt2dswjnnnj.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gt2yzupmofp.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gt2cggvsksn.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghmksizl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2uscdjshv.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2cyfxdruf.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gt2hplnkiyh.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2avjdwwvj.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gt2ccjxoysi.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gt2ssrwmqwi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2mzjilqkx.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2kziqmnzi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gt2dhexwnpy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gt2iuudqdkx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpildpqx.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqxfoyyh.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gt2wpydabik.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2gbmcjvbt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2wtbkvgoy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2vqruxzyl.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2nfcvdxiw.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gt2tidbilkm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2paahzgyd.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gt2kseqwzdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gt2chboiofz.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2wdhwbxos.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkluvmpq.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gt2kiekqhva.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2bytipdoo.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gt2smsqfovk.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eetzflqa.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2dpjddheo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddjfpvsq.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gt2abtazukx.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2ydwmhjmh.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gt2wcbtuncg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2crmbnkyd.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2nqhkartd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2cfuocsvp.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gt2hnarngqo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gt2hqiqsjdl.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gt2onynajua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyycjtxp.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gt2mghtwgaz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gt2zhxehkkb.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gt2znxbsziq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2upjogxsv.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2dbtvcfdr.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gt2cxyipdll.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gt2elmkkqgj.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gt2xrxkxfxt.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2kewjsjgn.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2vfidyqgi.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gt2dsfsnvym.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gt2lkvmnofi.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ihvdmgjv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvcxmssh.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2pxqunvse.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gt2kzxcrqjs.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gt2guncuehi.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgqcdtfg.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gt2gvuxaeqh.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gt2jeflqnpw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwaguvll.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gt2pccfduvc.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gt2brykmmng.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gt2ssmmhhtk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2moivjdkm.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gt2rhhhykka.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2yhtwawra.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2cuhufprx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2urnltagn.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gt2rfbtaheb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfbhfqvn.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gt2tiljwazc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2vbkcdkjn.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gt2cvgmhpmo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2fqhhrosp.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gt2cughlqgb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2djaxfjih.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gt2jyzzkizc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2bdbojagc.html


<!-- 参考信息 -->