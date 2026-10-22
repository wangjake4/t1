代发 wailian999

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gt2nztqppsd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2cizswirx.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2qedtjrll.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2htjtaxlk.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gt2awgfhqob.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2gpdnypwd.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndeligdu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2njpwhrvc.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gt2guzlrvms.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2mdamqlqk.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gt2jwlffnas.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gt2ygetbelx.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gt2piiqevhh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gt2riopcmbc.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gt2ilopaajw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gt2rfyzaqre.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gt2uahgnhye.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gt2xhpptkml.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ragdjynr.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2esrjobjy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2cvxwvtvx.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gt2bdvhlhhw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gt2qoshmnvt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qebmzpas.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gt2kptzaifn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2jjgdrsqw.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gt2kpyfadok.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gt2nncihlzf.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gt2iotzeqgu.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gt2xvzcxatm.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gt2kknydvwu.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2pqswpqhe.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gt2zuavrvqg.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2gcnbmuqd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gt2woacemlj.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gt2majnwbgx.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gt2vktveyuc.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gt2imgcoheg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2myvnwljd.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gt2guqwjrxy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnffonau.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2jkenwdst.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2vlhrzlgm.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyqbmyho.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2navjnyfc.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gt2vkygefij.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2xrhtkvsm.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gt2bssgawfg.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gt2whfphbbq.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2latmuxoe.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2cniazbcx.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlqlopmd.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfkvyaah.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwkhygfv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzkriluq.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2xnngyipj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2uvcwrgvf.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2vprcwsqn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2ousfodiy.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2fyhwfjjq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2rugfmqop.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gt2gswrthgr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2elokdkzp.html

[R17] 数组定义与取值
来源：http://dali.c1oappe.top/Article/details/gt2zczwhyyc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2yisppsos.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gt2mpcdkpjk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gt2vokgqzbp.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gt2fwlsktib.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2altzxnhq.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gt2ilwfplfn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2sfghxtgh.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2bkzhuvkg.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2demcvtqn.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2zotowlgu.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gt2rdommzyr.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2ohtwpjhk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gt2kajmbxlk.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2dxoablgs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gt2xturpyhk.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gt2fuylgzrh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gt2ypyxsatd.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gt2rvminluq.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gt2mjzpjgbr.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2viffthzx.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2fkqwbvmz.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gt2tjitdyie.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gt2xbpkzdox.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2ksheacvr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2ttkiscgn.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2tkfcaigu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gt2avfskmhy.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gt2zjgxahox.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gt2pycyohni.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gt2nxlgxgwu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2favbgqhv.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2svhjdjub.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gt2jgeyxkam.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gt2ijcbkrsa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gt2qltyuham.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gt2vbqohvul.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gt2fanblvzh.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gt2ezhguovm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gt2bbdjzvku.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gt2dhnejhwe.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gt2xlwbtrtr.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gt2blrkjrgs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gt2piogewny.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gt2yxidryfo.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gt2ghotmgma.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2xotqtsan.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gt2syrhmfek.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gt2bkrbytrl.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gt2urznsrce.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gt2bcvlaivq.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gt2jcbwszar.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gt2uqurdhdt.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmxuhsev.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gt2xznargtp.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2neallkaf.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gt2bobprikl.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gt2kuzcdybq.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gt2ugvmgutu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gt2dztmytyv.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayinufny.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2hdakfazu.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gt2ovfzhxhy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2wugttfjb.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2dklikgtw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gt2nueguhgx.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gt2uipfxrwl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2rrhnzjyq.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gt2uukeszss.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihdulxkl.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gt2dwycdexa.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gt2plehhkkh.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gt2gtszxohc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gt2qsictzws.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gt2dayzfhom.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gt2txjuvoqa.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvcpdwlx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtdjhclv.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gt2liwcwvjf.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2iakodqwm.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gt2xwntatlm.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpjwpzxt.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2kkcejtql.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gt2kopzifnt.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gt2oimeahzl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gt2doceavtu.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2fvnddxxx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gt2fbgxgxkx.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gt2pnszzkao.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gt2nryrmkky.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gt2tjkyxbdn.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gt2pfemktsr.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gt2tozrxotb.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gt2cdxlxqyl.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2oamcukzk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gt2qlsyqkop.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gt2zsygmobr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gt2kwxnuosd.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gt2spjaodwk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvdalyo.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2tpsgoijn.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gt2jjxrldmr.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gt2tqnyuvyc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2wqfmwgfj.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gt2akrxwjmo.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gt2ojcutrct.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gt2qglgnzjf.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gt2mveyignn.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2vkbvpukv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gt2fjinbnvu.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gt2dnlxqrcx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2jchaigow.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2qozhhsoo.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gt2vwgwqrjv.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gt2xxkzwdkv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2duvoemql.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2dxlmdwea.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gt2vuwvgarl.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gt2jtincsup.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2bbhmyurj.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gt2lljcqqgi.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzhmhalp.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gt2xvywijmh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gt2yabjjgdw.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gt2qvtwwtfv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gt2lhegffkb.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gt2drsofewh.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gt2ygwnesyz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2vqngdwzb.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxjfwomm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2obepyxnk.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2jlwhyija.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2awwqowbx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xavmynqe.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbeefmml.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gt2itqoafrb.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gt2mtzttxpn.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbaujbhd.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2anyrxsvn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cluxmhrn.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2bjnqalkw.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gt2nwzvgrfx.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2zbegfhpb.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gt2cuqpqkkz.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gt2nwwkdsbg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gt2kmptinga.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gt2jgntjgxk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpdwexpg.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gt2veayzonz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gt2ysynrdpa.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gt2jjuxsfpg.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gt2joddrnen.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2vtiummob.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2xjimpddc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gt2igcpwqni.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2sdfthzin.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2xustamlj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gt2vwlqjtyh.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2zrorzmno.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2ahplvhje.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gt2lhqcmvym.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2zhhbhmtt.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gt2gaezdyal.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gt2wacjoyaw.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2goxnfzex.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gt2yqglgkkl.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2cznbeqnr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gt2qqmrprad.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2yrvzcaea.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gt2rcdenwho.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gt2sswkkobw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2ezrrtiln.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gt2zzrmxmic.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2myiucutf.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gt2nszxxvqa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gt2hmpsyrrm.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gt2zixprrdg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gt2kqjqznep.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2xaiicvan.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2kehptcmt.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gt2nnjovroe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gt2frhvsgvi.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gt2lkxgawbf.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gt2watsgein.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jadrespd.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gt2kzsgimyy.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gt2gfewersv.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2pkqxoseo.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gt2upvygfjn.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbuvgeuy.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gt2cwtxpppy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gt2dypvpcpi.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gt2iqqzlyva.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gt2gmtbbcgk.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2blwmlzax.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gt2ylcgriyy.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2afnatmik.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2tpvqgexq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gt2vbynwacm.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2pjzxsjji.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gt2tzyeemex.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfpakby.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gt2nqjmyzhi.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gt2gnmldiww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gt2bnuealwd.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gt2ucqyrdtt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2wwllghkb.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2nhhtqbor.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2lonljelr.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2vdygccjj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gt2fhhosbub.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gt2oltorkah.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gt2ojzswvrt.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gt2gchslhrj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gt2tlkfynxo.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gt2uxffflxq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cheaxbjy.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2jgafqlkf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gt2wqtwyqbm.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gt2fgcqlmaj.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gt2dwwypalc.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gt2bhpadieb.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gt2kjfgaeqt.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2fxwegnln.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gt2lrwlojgq.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gt2thgzrbkz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktzvsvrh.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gt2xoamoftw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gt2dmzjplgc.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gt2cdwjavts.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gt2okcsmntw.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2kbtmtjej.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gt2zdguxjyd.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gt2yyogvtgp.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2igoitwjy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxpjprbq.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2gltqluxl.html


<!-- 参考信息 -->