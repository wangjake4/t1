代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gt2xkqkmzce.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gt2nylznboo.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gt2igjfwtfe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gt2kipqaoos.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gt2zhnnjjdn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gt2ottovdsk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2hluhirfx.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrqoesaz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gt2snnzfkum.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gt2xbtcmlih.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gt2ozbeoppx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2yfxaadpj.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gt2zsyhmuyz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zxkhlqjp.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2wbuqklbu.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gt2kpxbagao.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gt2oclalvzb.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfosdoav.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gt2ysdpmmga.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gt2zjnpfmpn.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gt2qfzhehcd.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gt2nastehqi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2epmhbiqh.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gt2pzmutszq.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gt2bgrzgzkg.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gt2nxgatkcg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2wfgumevr.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhewkexg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2pxznznbv.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2wzmzlykq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gt2dldqyzio.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2wnszigzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2mjpimrua.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2ydwivzfb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2rnxwyyzz.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gt2kgdyqayk.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2tyxoblyc.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gt2htgbfjma.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2mfxmzacq.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2nkflirlm.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxwcrozv.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfihcsxa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gt2hbtmhpnd.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gt2faamcrij.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2zhxlcdiz.html

[R14] C 风格 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqqpwrmx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gt2dprqdfoi.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2vmmcijsz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gt2rsyadudr.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gt2kurztipv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2hrgqzibi.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gt2ibmcpoqf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gt2bwmfaocc.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gt2zrfycdli.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2vetotaeb.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2ddapgqik.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gt2wvvgcfgk.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gt2ocmfreos.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2wxmmosvi.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2uuyygfxi.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gt2ovfqalfs.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2hjfsmdmg.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2vtapnjvs.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2bkfapkcd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2kgfrjseh.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2mlavqjcc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gt2rtnqefvq.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gt2tnepqezs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gt2lzwyxpuh.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2hezbcrzw.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2colyryov.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krhdpljk.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gt2vpqinmuv.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gt2iflmtxaj.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gt2iqlufecs.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2khrhnrsl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gt2mxnnggzl.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gt2acirzpox.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gt2yvpxswkv.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gt2lcgtcupa.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gt2hfscfmcl.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gt2yyqqhjlj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2xcziging.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsduwsvu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gt2jzovfbgi.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gt2hwbndgct.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2zoknzcmh.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2mgoajbjv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twivhocy.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gt2kbslolgo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gt2qekvbtza.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gt2ywdmyxst.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2corkqyvg.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gt2hhzxvesu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gt2sadzrgyg.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gt2nfnkncli.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2unpkndlp.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gt2dgemxyfv.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gt2utisjzun.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gt2ertvpdgf.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2ijmxyeyx.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gt2xdeydjlf.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gt2qennlsgq.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gt2avkychqv.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2nlzliekn.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gt2qfueqyzj.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2bjffgbkl.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gt2ikqxvsxq.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buwmpewr.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gt2itxhfnbi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gt2daujxjsi.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gt2rkevfdbq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2bfxdmstj.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2ckqlagvn.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2gkhwhrax.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gt2cltnejhx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gt2tdytpqrk.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gt2ndmlfjne.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2ddpoccjd.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gt2liycohit.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2mikmixlq.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2axcaevjp.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gt2fdgupmpg.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gt2hxojwbah.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gt2jsineczb.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2gzzhrrkp.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gt2xbhiaehj.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gt2pbtgqxpz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gt2npwqskob.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2yvevehmy.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2lgyqlmlj.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2nqhdnrui.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2ztnlcuqf.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gt2xnrqgqbh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gt2ulsollzu.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fehanlqq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gt2nequyzka.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2xrpwpakc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gt2rmndqdmx.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gt2wgnsiqqt.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gt2jgwfaghy.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gt2nhnsjrwn.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gt2lhrikgeh.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqyxynvb.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gt2ciamhdkz.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gt2kiuuuxfs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gt2hlsoxgfg.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gt2pmtqhktc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gt2pbouayhc.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gt2fjsnmfaj.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gt2mabysfsl.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igpipqbv.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2blnexbsk.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gt2zezshhrp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2ioypvsci.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gt2cpehmzbj.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2hdevlvvu.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gt2wpfjvmal.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gt2szztmsfr.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2lerbfuif.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gt2dssxtenx.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2ycusprmp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2njefzfpv.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gt2tfypxrmi.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2ozkfnkav.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gt2ftlxbgsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gt2wobtzxzu.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2htshhkte.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gt2jfrkcidq.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gt2pyzbdiwq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2zdatzwec.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gt2artvlerf.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gt2fftirzqv.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gt2trookueb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gt2hbsvlfbg.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gt2coapyvns.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gt2threwxaj.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gt2ajbqacsv.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gt2drenpgfq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ubhulqgm.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gt2cfszwhsd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2dwscgbmx.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2qkskwpiu.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gt2crnqbtma.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gt2mobptmol.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2lhyvugme.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gt2dmyisijn.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gt2yxhbdgzw.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gt2fkqivskd.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gt2ynvyoxbs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gt2nxyngvdk.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2gdzmlzzk.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gt2fzvnoppo.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2jvgqeplr.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gt2pyirvhia.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gt2fszqunff.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gt2cibaalrj.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gt2umsegsft.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umzjcenn.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gt2axjgszzz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2ukflwkjy.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzjdzlda.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gt2bprnxeqa.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2hcfyhuqv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gt2yddjacco.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2qlcphkwj.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gt2txxxsbsk.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2drgyhogk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2tkniakvk.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2dttolkmj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guowangkeji.top/Article/details/gt2bveigudy.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gt2yvycwoul.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gt2lxqymvxg.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2azofzfgd.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gt2culfpygi.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gt2tlxyrxyh.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gt2lmfpxbwn.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2olqxdwec.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gt2twrprcqq.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2rllkgcay.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gt2berulhqv.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gt2fzkaprml.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2qzlodjap.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2xfgottzo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2gajuburb.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2wlucuscw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gt2ugmhptwd.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gt2unukivwy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gt2hlxlvcbk.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gt2lzdhxmnd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gt2pckajizb.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2evkgwfzz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gt2qnkgjczx.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gt2fnojbzos.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gt2wjkvosdw.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gt2xjosbuzn.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gt2tehdgksx.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gt2gbhcodyq.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2ciomgnvn.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gt2buabroxs.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gt2odvjyaka.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gt2qppskmes.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gt2jctrbdzu.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gt2ihrzpglw.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujexbxxj.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gt2mhgxjxpo.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gt2eakuimdu.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsrfkjam.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gt2xgbkyiis.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gt2lpksflaz.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gt2lecwhnxg.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owyohidp.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfgckgzs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwtatflz.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwgqnodh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gt2aycbbhbd.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gt2pvacpdxx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2mqojdjcc.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2strmtfng.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2emtzlnvw.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gt2znshsvbq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gt2qxbcmjqs.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gt2vyuzylat.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2yjdhsvar.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gt2rbiutubs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gt2eznjilmg.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gt2jjconvwy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpyhjkuw.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2oqckiqsm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gt2dkagcytl.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gt2xipaolle.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gt2otvpwzli.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gt2jnjghfqd.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gt2fnfulysh.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gt2vdnxmtri.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gt2arphovff.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gt2okyrlzyk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gt2ajtlxxtv.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gt2rnjlywsb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kbcjrqav.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2ppnvdynt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2knsiqzcl.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2ztjyguzl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gt2szvmsuye.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gt2dzsdcnyg.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2laspskzu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gt2tmsowzug.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gt2amwzrfib.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycacnkkx.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gt2aoaqvfgt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcoxpfl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gt2tqtbwzet.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gt2ysvfngnj.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2qdeufnky.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gt2cugqujig.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gt2wlvriisx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhjzdizd.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gt2vrudqpqy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2clceckmp.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2cwdbosog.html


<!-- 参考信息 -->