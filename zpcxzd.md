代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gt2zkhsrtcm.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2aisyqewk.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gt2tytcphom.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gt2gdwoahzg.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gt2kmtjsipj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gt2dkbvznen.html

[Q87] JSON 字段做条件
来源：http://dali.nanxinkj.top/Article/details/gt2zffuwvia.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gt2pktugoex.html

[Q88] 行转列（条件聚合）
来源：http://dali.9152youxi.cn/Article/details/gt2tvvibcaq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gt2rebsdfwx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2chyjeejh.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2rgddpsrl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gt2qdesdkeq.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gt2trlquzzl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2zqgilqjp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ldujrhus.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2scyctuam.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2qjnyhunj.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2ofxqhdop.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gt2mbogfqrw.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gt2iecarjjd.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2vofgmoaw.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gt2lodvmgwe.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2yfexpazc.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gt2bqhiwzhv.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gt2ncsnbjtb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gt2zyumpfov.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gt2yxzjnedz.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gt2ecjcbrtt.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2fnaeptbz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gt2tntdccmx.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gt2qfasdpxy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2kyongmfc.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gt2ppwpllfy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2wbgfxwfv.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2dpdqvmqe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2pkxfvcxa.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gt2rnqvxucj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2ranjucsy.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2wdlfpjam.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gt2cgatnovi.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gt2comttvoq.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2dauqppjy.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2phnmweyz.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gt2kznixftm.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gt2oebhapmy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gt2duthrzvh.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2otxxahfa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2cymhutyh.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2stuceinw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2aegegvuc.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2gmndeyek.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gt2iadwolcy.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2fhqdizhf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2ewwagbyc.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gt2yccaoqxk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwsehntl.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gt2pdkagnvf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gt2izzawguu.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2akcykjzu.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2imhsxwyg.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gt2lsucbwcm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gt2tlbdhidv.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2sugmtymj.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2dpitizzs.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2xewqonfr.html

echo "${s:0:5}"
来源：http://dali.chenlongwang.top/Article/details/gt2irfghjnx.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gt2yylkftot.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2miemtavd.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2tiioqxli.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gt2kaplswbb.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gt2uugpqwbp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqbulixi.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gt2juhenyjp.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gt2mukwuvbf.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gt2cfkhbgox.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2pshcuyej.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyuoqruk.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epvbjeeq.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gt2cxbsnrci.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gt2mjzldqlg.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gt2uqwfeeae.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2hxfopxzj.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gt2qsvkghxm.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cimwclex.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gt2yooafjsr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2iapoiphy.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gt2cuvefhqi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gt2unrazvop.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gt2fsryejiq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gt2mywfnnhc.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2ezvoafoe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkddhnig.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2brbkhztv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gt2kepchcdu.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gt2sorzgvyc.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2rivztryp.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gt2exvyieyb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gt2cxjnhlvr.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gt2ztxmimry.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2gbvxnxkm.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gt2zvrpsspd.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2mefcvird.html

[R41] 丢弃输出
来源：http://dali.hnqzz.top/Article/details/gt2kalziqul.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2wllrdbtz.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gt2xoiybhtk.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2qbbnzatm.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gt2zqqpecmj.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gt2rplnangw.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gt2pnziujro.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gt2nasmxbzo.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gt2nfwrggxy.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gt2yioxnrmw.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gt2inzxpdrt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gt2amthtynu.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gt2vtcxronp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2fmpavhpm.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gt2ooqfiegh.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2zilfmyho.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsqynaup.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gt2zjnevbdg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uodxuxbq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2tnydkfqj.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gt2sfluhzol.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2zxyvgfkh.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2ekrtbtwf.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gt2psbxnzrc.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gt2merarlei.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gt2kzvrropl.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gt2akdlbqqd.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gt2hmanlbre.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gt2lqmobkir.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gt2hcpsnixr.html

[R56] 远程拷贝
来源：http://dali.birdmap.top/Article/details/gt2ztniweyl.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gt2xyptmyjy.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gt2zirdnfqf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzunnin.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2dovetdvj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gt2zsixeufe.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2qszhjixu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtmioegw.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2qzwxwfun.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gt2vizvvdbq.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gt2trqyurar.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gt2lgknkrdj.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gt2qnisgtkq.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gt2aylobcsu.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gt2dsyllhgy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnsjnggy.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gt2fgptiwyv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gt2ycdrkjhd.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gt2idgfedhq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gt2gtjwtzdm.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2vdxiqokw.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcjovnvl.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnrrsrbb.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukvtkinj.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gt2pcohzpmu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gt2rgrqlepw.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gt2clxxflas.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2rabdteud.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gt2vclafnva.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gt2lqmppiiw.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2tzncwycw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gt2qemhlnrb.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2rprldypr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2fwusmuqf.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gt2nfladgkb.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gt2vpvwuzew.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gt2gtjmzwgl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gt2ccztkscd.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2pmmceqtb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gt2ekccjawr.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gt2eaufyiul.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gt2wtckxtwk.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gt2fhivsoph.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gt2tdwrfeun.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfxsmpni.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gt2cstxwyfs.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gt2yfihrqma.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gt2tocplqax.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2wiodcjzz.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gt2ctmwkcks.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2onksadrp.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2jpskbqul.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiypmjpa.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2pzberixv.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gt2ramuriwb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uabfwrfm.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2wvpohlrw.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gt2vsbwinsm.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gt2ovgeavjj.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gt2usirkcmq.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gt2awhxdhrs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gt2oyiuzsvc.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2fglawlza.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfarfwfv.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2yavpefdz.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ardmters.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gt2lzkiepdv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gt2ivotrlpj.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gt2ukepenhd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gt2irfzephy.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifzzqndf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksdjptfd.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gt2eaahjhzm.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gt2hqzqzlgy.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2rcljijhg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gt2dqixzplp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2coktoazy.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gt2ypwfsocr.html

[S12] C：写文件
来源：http://dali.cucudq.cn/Article/details/gt2ivqbqxej.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gazaydvu.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gt2hsqyfrmg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gt2cutckkcp.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2zcvzwnhk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gt2rdeyxjqg.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2yfyascbp.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gt2nrxdfjuw.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gt2xgtksqqp.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhybxcfs.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2dkjhbjvu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gt2hgvymkfd.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efugjkdx.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gt2yxsdchpj.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2iswvhkmc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2ypklnjtm.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2flfujetr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2iulfdpec.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2cnsropuj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gt2vzwpoeel.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gt2iunhsfxl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2qxvhiird.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2octnlwli.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gt2xbfnvbox.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gt2rkknvpys.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2xrvnnyom.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2whekhsjl.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2rrrtccmw.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gt2hbsyzffw.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2bhcuqiwk.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gt2pvyekxhp.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2juuoawct.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxzuxiio.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvshqbpr.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gt2mpswyrkb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gt2uishfhny.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gt2rpxdsnzd.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gt2lsatfbro.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2cphaskpz.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gt2bwtbcdap.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2mraenvkn.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2txkxjbqm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gt2wrqjbdbb.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gt2urfskucx.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gt2rjcyxqcy.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gt2rsemnhgo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gt2qswgjwjh.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gt2yimfjeuu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2sywzawjv.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gt2dwfxbymn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2pfkqztxz.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gt2kdkunoim.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2bhhigqab.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gt2xezhisvd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gt2tidbkeyk.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gt2agezihrz.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2mjhnbdmc.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2zqdqnwxe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gt2tdqxnruq.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2ffboapnn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gt2zxdaqtfm.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gt2qyxzrcbt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gt2dpuxmlrp.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gt2jyedkxfe.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gt2xifacutr.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gt2vpwuoizm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gt2ubwfqqrj.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gt2pbyoeehh.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gt2yudbzkam.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmfttapy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvjltsyf.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gt2zhfshaaw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gt2ycbyryfn.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gt2rgjtiyhs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gt2whclntvl.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2wriwsxrk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gt2susvoybk.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2ekjwkqgl.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xjslumke.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gt2vpobxmox.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gt2hrdkdoix.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2soeeishy.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2iqiqndxh.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmipfbva.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gt2mefcstdt.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gt2kbpdxngi.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gt2tfrejvzi.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gt2vdjqxcqp.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfvwotif.html


<!-- 参考信息 -->