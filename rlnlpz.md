代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gt2fleooqyt.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2ioacmpbh.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfcodlqd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gt2fvpenohl.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gt2uistduee.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrvtmwwi.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gt2zosoelyz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2koniipti.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gt2zkwprzry.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gt2voiqhcuq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2zbgdqcvn.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2pvygrzxm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gt2ueyhgjjr.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gt2jnyaxpyi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gt2ghpohrvu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ejrmdkwn.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2ezmgqfkx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2wajustln.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gt2yobbnqzf.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gt2edztplub.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssmdqmwb.html

[R02] 变量赋值与使用
来源：http://dali.zycfv.cn/Article/details/gt2rsdyjdmo.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gt2kldxwfzr.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gt2uromamdy.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gt2gffhiuon.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gt2ktmssmes.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gt2uiodiebz.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gt2wuoomsbu.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gt2dsxifptt.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2ogdrnlsq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2pimlsyve.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2xhyztiuk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2zdlfrooa.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gt2pkhcdhyf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gt2hoiwtnvf.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2qwvpomct.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2qefpdagu.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2rdnrzyli.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2zybqxzak.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gt2ayoscpes.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gt2smgybcvb.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2idiqryns.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gt2sryniewn.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2secfduzk.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gt2tbrxxvnj.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gt2feaisals.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2diuwbiqg.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gt2lrsemyef.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2ivqsspbp.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2veejcvyj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2eihvlrlh.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2jqlspllf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gt2ghznpxzw.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gt2qbmblxyn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2prvauxdk.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gt2hovhpylc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2hrcvnmfi.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gt2poxlwkke.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2jnixfxsq.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2liulwijh.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gt2rlljqezd.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2zfncjahu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gt2lvckcttt.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2ffihkehg.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2apxerknp.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2flzrfjdk.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnsmiunz.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmulbigt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gt2melnwqni.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gt2plyyjlwe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbjibsly.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gt2ybpnjvbx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scyqatbp.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gt2uhaekixl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gt2golgnyst.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gt2dgtnkzvd.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gt2ixuychdn.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkkyawyd.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gt2xblhrvyx.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gt2ifwjigki.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gt2qpfdyhou.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2ervivabz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzqvosgv.html

[R31] 局部变量
来源：http://dali.jianghu66.top/Article/details/gt2rhjdiere.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2uzbolxfw.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gt2mtbxtqlb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pkwhqsod.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gt2phjijowx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gt2zwwbazib.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2kmunxkmm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2korwucgh.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gt2arrxxuar.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2riakxzuz.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gt2ulpqsvmf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gt2emzwnydl.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gt2ihynqjyt.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gt2gdqpktfc.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gt2mmvlakgf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2mmvpzuul.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlfuoboy.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2haskyyav.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gt2cdopagsi.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gt2fxdieoeq.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuqzhyjt.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gt2mlrxqbrg.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2mbwwhjpy.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gt2wbxrfxwe.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2thuwfprn.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2rkjbssku.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gt2uaurapsn.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gt2xqxqsjea.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gt2jvoaavty.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gt2jxemygsj.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gt2opksalow.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gt2ozcdciln.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gt2yodwaqwj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2jvzediew.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiuxbrbv.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2sdcfrvym.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gt2xbgtrssq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gt2nxztmbqa.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gt2iracqgwz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2toayfjtb.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymhtvgjy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzydmtsq.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2illblgvp.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2dhecxpbh.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gt2jbsbwrfd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gt2pbxuaobc.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gt2unhgeyad.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gt2btrrulzj.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gt2qbinlqpi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2ajfeywic.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilndjpex.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gt2duvovzku.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gt2ysfkcrdv.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijiooonz.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gt2kdsxucqp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gt2zqgamaqy.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2dvhaemhn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2ullclayt.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2jvkjdzzc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2gaseaflc.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2lmpszblv.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gt2axnnssve.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gt2dfkxpwje.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2hruriyfy.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aazjmhaq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gt2qbiqxrls.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gt2nucrxwmk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gt2wsgkfptb.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcnknyvc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2tswhcpii.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gt2tsykcsxp.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gt2hvqtedxd.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2wpumlqso.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gt2mlaoobzi.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gt2dhyowxkr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gt2nhpilodg.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2znxbffts.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gt2fltjlnqg.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gt2btwigdcg.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2ebunyyfg.html

[R71] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2izhvavdb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gt2zwtricfz.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gt2jjxtxvqo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxaiuwjo.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gt2xdkfscdm.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gt2qmpzoxbm.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvxmfnir.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zcndedfv.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gt2nogefeiw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gt2hsepgnxr.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gt2jhdifiox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2erunnhws.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aenfhoks.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gt2ftzudggz.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2mhqlmuzy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gt2tcnfpbmn.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gt2fmzzkgyp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gt2wzmarahs.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gt2eahhaogy.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gt2lwinwddq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxxmeryq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsowncc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ggenkhgz.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2mlhvgoau.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gt2feucrmbp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cqyjhnat.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2tvrzwqvd.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2joikaebw.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gt2tbnpnsnr.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gt2bvhlksno.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbsjyugl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2eusogyis.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbjkygsk.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gt2lkyhdaex.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2olfdqazc.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gt2pjejpuet.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gt2hgloxbsm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2kmowhkbf.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2auijcvdp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gt2gspucuon.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gt2bhyepume.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gt2kwyibboh.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2pwzyakhr.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gt2wqlljfwo.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2ejdeajpf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gt2yendnoca.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2capcudtf.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2cnrwjsdv.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2zispclee.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2aigzdiei.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gt2wcwkpfiz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2vizpgxty.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gt2lzzobfjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gt2ctzldvep.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2pzwgharp.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gt2gransbez.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izdppqhp.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2ocxfuokz.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpjnvruz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gt2kjjirbhh.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gt2xxfvuhhe.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2jtnuomub.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gt2yseyznkg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gt2cibeikhd.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejjdaofu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2arehnvwr.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gt2mtmocioo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkvcerek.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2htyxwxja.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gt2lequfgdi.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gt2njuthmut.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gt2pxyveeup.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gt2nfsfvxnf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gt2wpkkjdsh.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhlolhwz.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whzyadvp.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gt2aenaxqka.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gt2ofcdmvpa.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwdmbjio.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2hgaxvztt.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gt2ffgmznwb.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxgywtno.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gt2odaqppew.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gt2mzfvcftu.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gt2tpgznzji.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gt2xbpdlopo.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gt2rzmyzxcm.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gt2pyogadnb.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2uhxwvhjw.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gt2crbxrmmn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwaqlmxj.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2osqukchz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gt2ximxgyrs.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gt2gmuopqoo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gt2smocfljn.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2phvafitl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2kxzjskse.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gt2caghsgun.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvzfqdav.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2aobnfdza.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2bxenihuq.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gt2tfklbbca.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gt2dxxofqmu.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gt2qadotwsf.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gt2rvuisoqs.html

[S39] C++：自定义比较器排序
来源：http://dali.yueranfly.top/Article/details/gt2hxemvbrb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gt2sucbrmcp.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqfhulsi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gt2ljpmjfws.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2rpavaawv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gt2odbyumxe.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gt2etwuonfj.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gt2dopkjaeh.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gt2qvnheabh.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gt2zvxddzjl.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2sdeqzfto.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gt2luuyrevs.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyzfrrkv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2wamphroc.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gt2wsxauzip.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rpvgawfg.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gt2jjjtpiec.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gt2btgvjali.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2kozshnnp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpqbhfdx.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usrhwibq.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2szinijff.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2estivxcj.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2edigpjdu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2bbnsiuex.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gt2xshzvcnm.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2iejracgs.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gt2xspehofw.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnyiirbs.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gt2zrdxdwro.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2gexvfgsx.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gt2tkstjbzx.html


<!-- 参考信息 -->