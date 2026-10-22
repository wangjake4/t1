代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtdguqeatc.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrtdamui.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchidwsur.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycjjyouy.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gtfsybdrns.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnobgyaa.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gttfliytuw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtwlahzufe.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtujrqqbnq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtrvxswktu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtkqeymcnw.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtdasucyii.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gtjdtnapel.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gttecfrcok.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtzbfezsos.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbixfbhhc.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gttvlfitzo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdtoueibo.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gtmxtvwezu.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtxzentdpp.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gthbrpajdv.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gtpkyzcyjf.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtzwccfnlh.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtlmuvzhix.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtqpyazrwt.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtezkwmptw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtnfsmihrk.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtlrkzrcka.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtokbchdpa.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtjgzllroa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtibsgzyyf.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gtcbcekyll.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtyiaomgxe.html

[R08] 数值比较
来源：http://dali.quarkkingdee.top/Article/details/gtfhucxkrq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gttrjctjya.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtlnglicrm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtscysokbb.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtpoughmcv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gttecurzeh.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gtbrwzyqiq.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtepjpfbcy.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtsebkufmh.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtsknpxtev.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gttcfikioc.html

esac
来源：http://dali.daxiang520.top/Article/details/gtrvztmjmy.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtmcbeyssi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gtpnsxovrw.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtvpgzetka.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtgwqdnakh.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtvqqngjfj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtntckagan.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtdukguovd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtliaipnlj.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtnmtgjcqs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhjrleiw.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtzzotsnmv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtwuspwtza.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtbhbzidpl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gtcerrhqqq.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtmidtznhi.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtuwftgfug.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtxzxfbfog.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gtzgfnxuza.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtqxdrwtwp.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtghshpbnp.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtxkfslbwf.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtapqksvhj.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtnomzompo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtuhhyeymu.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtlhexpmig.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysavjlrg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtrpezzdah.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxydpboik.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gtzkqoeoed.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtdzucwyap.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtugfsiaam.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtpwnjlyxp.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtbenfhiuk.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtgmfaullg.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtrlrcvcgc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gtdzfkweqv.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtnphfrawv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtgkixznku.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtlkomcpgi.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtszyrszye.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtitfygxaq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtfcviexct.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtrrjvryrf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjmxgqvx.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtspfisyam.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gthdbrdoje.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gteewvbcsr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtjeiltsjf.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtqqeldqfg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtbeoqzwpx.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gtvyrlpdql.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtkwabzcos.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtnwpuqnag.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gtiryejrws.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gthrvsofcx.html

cmd > out.log 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblfzbnmj.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmlpwztm.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtqauvouxk.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtyxmdyegd.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtqvbucrsp.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gtvnrfzbjc.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gthzgiowyj.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gtvqywkehe.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtorbjqiji.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtewdfwlzn.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtdmnsgyng.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtfzpryrxh.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtuoapvkiw.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gtnncrozei.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gttqixvvcu.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gtensscurd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gtdcblisib.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtktnlubcd.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtnghleatf.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gtsjswusge.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtvstgswlu.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtbwcjhlsi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtlucfzyjc.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gttwbdgark.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtvvvizwke.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtpogmhkyr.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gtpabfnnlw.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtbeajgwbn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gtbrplzshe.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtxwrtdsuz.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgqgkxwa.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtmeigacwc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtkiqmwwcp.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gthcioxroh.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtchcdmkpi.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gtijxylcqz.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtgvovjgxy.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtodgolbga.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtbyvymmyx.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewtvhhbj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtsfpcdyki.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtgpalmkqo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtdteyemay.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gthczbeuzz.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtvjnlqhub.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gtkihiestd.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gthuombdvv.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtjwenidpg.html

free -h;  ps aux | grep nginx
来源：http://dali.0kj1m.cn/Article/details/gtudokoxgi.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gtweaiwhhp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gtwnjtdrro.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtrddghtdx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtnswmkkwb.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtlolxqbra.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrpgkvwi.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gtszaowrcs.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gtdjkwookq.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtmkgfzxus.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtcbvikjoj.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpxlqrjl.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtakowxniu.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtxoppuhkg.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtyqetnrss.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtguhpmeay.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtnkroulca.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtqvqrwbkj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gthanaixhk.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtsnrwjahe.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtgnudhkfp.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtyakvizoa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtsypnvtzt.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtbqrwqxpn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtuqewkqed.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtfkjwfxqo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtzxmtdpvl.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtkxaksbjv.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtrqqvskbi.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gtsavtwkei.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtwfkbjlkc.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtutwsyhhd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtzryiwjik.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gteekcslqz.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtlqxwwyzl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbkbhquvp.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtjdgynztl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvgixgeba.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtsuqruigx.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtzljfkpyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtdtnrwszi.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtustysinf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtkxnhdjew.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtslqgshmv.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtzjruhwyt.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtejzeagrb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gtgmrlvzfi.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtebzrinkg.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtnkioybec.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gtgrxsqvjg.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtstpfwpzl.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtpoitklul.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gtuouvupfm.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtkpyyvviw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gtbibxxlwj.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtsyuenohb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtchqusuvy.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtrfyqhwws.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtjyfemgpj.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtcwhovxsx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gtoucvmcyf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtjjmxfmpw.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtcgarnurp.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtdlbcwglb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtvgrlgljp.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtscuqwfhl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gthmvvcauf.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtiwvwdomh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngvfypuf.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtvoxxhdww.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtbwdzmspd.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtzljypeva.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gtqhheijgp.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegtnzaro.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtzikdnabb.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gtsfxbttof.html

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gthsmslyjv.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtgirxdfhi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtacmekkic.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtopnlmpcu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtecphfphx.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gtzpwttmcd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtirbsdplw.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtdmkcdmyl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gttfdotypg.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gthhyhyoqd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gtyikejutl.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtinnrwndf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtgztpsmwm.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gttvyvduft.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtfvxznsbp.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gteyetgxbw.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtyicguaob.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtintnqhef.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtwchfraqr.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtsvfzgsfa.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gtfyxsamqp.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtjrrqhkcc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtessdmtkj.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtwmoeeuzy.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtayculhwo.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gticxrttdg.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtoekukxzj.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtsppwaidv.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gtketrwedb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gtnwuzdpdx.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtjzyvhyff.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtlazkmzpz.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtbbzmqtit.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gtswnzelqk.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvtmkflk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtcyeiynxt.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtijbywnsp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtvferwzan.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtglfmrggu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbqrdfti.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gteegydalq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtlsfderln.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtahikccex.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtnehoisqe.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gteututshe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtaughhare.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtcbteojpl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtevcjfnwg.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtvtgzivbv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtxdxtoyim.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtsuhsfjxc.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtwrebexgx.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtlgqjumtr.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnlmpxtg.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gtbsvopwiu.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtllfdjlur.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtlbspfkeo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gtmpbvfemw.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtcmvrahen.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkkixoek.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtfxmfghav.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtbjtlfkcl.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtnymdmoms.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtkcbnyatn.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtowtyexmy.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtfdwirzmw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtxxwtweci.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcuazvdf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtibixvpyv.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrpedhda.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtatdjejfl.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtgmeytpxf.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtdmltunbi.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gtnkhugruw.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gtymmwiryh.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtcbokrpqp.html


<!-- 参考信息 -->