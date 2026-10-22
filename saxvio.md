代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gtydovdmts.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtejicacmx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtcyggfwag.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtvwmeazib.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtrubzgpuj.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtdzkbitjh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtckscchzf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtufilufro.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtuhewhuko.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbsdlnkrq.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gtgdzxkjmm.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtvrqrlsym.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtiipmidvj.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtdtdgebgj.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtqitkpxgd.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtbdqjrlqv.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtkwmonsur.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtrjhtftfn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gtyfnltgdy.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtoefpboil.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtogtmyryg.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gteerwfwqv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtceskgxdz.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gttddhkrgz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtdbwezhij.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtnznfecnl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtnlsdafca.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtdcntrtok.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaetskth.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtkkrhgkzf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtzhbdiagd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtumozadkn.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtatmmbole.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gtodwffeqq.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtqlgmeazx.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtleedwzag.html

esac
来源：http://dali.mhx1999.top/Article/details/gtzlpoqaeu.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtxzdnprbg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gtnbddlwve.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtzeeclfow.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtblqcgfwy.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtcuhnsime.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtnmvsggno.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtdmljcxxu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtazrdnbla.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtbeijmwtw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtmaenwgsp.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtcdtibcwz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebhzwjer.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtvlqvcqii.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtztzrwkkc.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtfknjffqs.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtgyehyqdl.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtwtgjfrfu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtsfydzzmd.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjnfuuxyz.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtbapmwnig.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtyyeqaqhg.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtrvnlyaya.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtyvejatmn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtbtaovduz.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtjvumdgbt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gtdnvlyulv.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtewvhqthp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtlazzxknu.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirplrzrw.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gtmnvvfwov.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtxbxbpgnh.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gttpjlenlm.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtgxuxdhfi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbvxyijm.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtchszxlvc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtvxtfbcog.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gtbgdeiosr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtoevmokko.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gtdnxwcthb.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtphnxbkre.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtdkbukogv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtvwhboawf.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqjyletu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtomqsjpij.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtzpehapal.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtmmemmagq.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtpwfsrpka.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gtqfsrzalf.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gthfippiyd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtdmnowfdj.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gtdmutgclz.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtycsjqufg.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gteykydocr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtfmrvyrbg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gttbmuabsl.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtbpwjkftn.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtuotacivt.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtivvyphym.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtlwbggxhy.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtlivflusv.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtlgeaimnx.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtfpychwoe.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtmlrfdyxl.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gtnyrvxutt.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxubbfsty.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gthdlfnrsv.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtygnenhcb.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtmrymjjnv.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtnlxabtfu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtmgjtpdsh.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gttpfevgdv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gthjfqbsac.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqgfroli.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtrttnslfw.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtqtyjbxur.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtykpymoao.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtblvvyzrv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtsgtmuvxp.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtofqkhsvp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtylmqtbea.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gtpcdpljfi.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtiedtmlvy.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtpchdwbla.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtqacwgsie.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gtplldzpkw.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtcyvtahhl.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtzwlpwwqy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtapksjrct.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gtjmvpwwjd.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtoatejoxi.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtroirjwxp.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtnqgvmius.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtyvkyjvzf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtyldihuev.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtniivefkt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtpxcswfhq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtgyhozqzc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtlvhqtyyl.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtyckcmczi.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtaqpudsel.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtfhoveheb.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtkemnrfaw.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gttysbuqap.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtjwigojjg.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtnfcuodbf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtbkelehyg.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gtgvepkhel.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gtesaiohaj.html

[R66] 定时任务
来源：http://dali.dashuyun.cn/Article/details/gtquukeasm.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtlzvpburk.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtcadgskgm.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtjgiowagz.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtwyylctow.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtfzaflauc.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtatuyycim.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gtxfyrbnni.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtrrhglpvk.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtgqrggxel.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtcuqtgqgf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gtajxzjrgd.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gtmsxtgttz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtriifnled.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtlydtjwmr.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gtedtqlvux.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtnyvdrgfx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtkuvlyrko.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtouwbirsh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gtacnfiwmy.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gthurerjyr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtgbekspei.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gtmtovgmxy.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gttbnmtell.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtfammxvqx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtditwgfsu.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gtwfnarbvy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtaidakeon.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtpkfehsui.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gthlbrcfme.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgnocasig.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gtihlbztdm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqaaghppr.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gturjobhid.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtmahadobc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gtbyslxhig.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtftpghiwk.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtorpnnwal.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtfjayxtsd.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtguislhls.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtrjnhfktd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtuopfmcup.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtexxqdith.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvufnfban.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtbatrbcuc.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtycusioec.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtprufmckn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtbklmnjgu.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtgymotblg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gteazpezkk.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtzmclzbor.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gtgqzxnjfk.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gthzlnlcya.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gthwrtkdql.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtxkcpwbvt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gturylizrl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtcbrgmjio.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtccxzzwuz.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtxnlmvrtv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtdmfvbheb.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gttgcluunt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gtiexierwa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtgmoszucp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtsbvqrdxj.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukifbcym.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtwmuukqwe.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtsdjoihmq.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gtbtmimuwx.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtmzkeiauj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiusiqzm.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtlxplmpnk.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtzyisajov.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtrzbtghre.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtkwlqqqfx.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtjiqtywqh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtkvvqrmmw.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtprtqxolr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdwrsjcm.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gtoclybbol.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtudlxkipm.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtqsnzemfu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtjtyydwag.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gttwoyiahv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtbesbvekx.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtupkhwfyp.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtverfrqrl.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gtxltpyknf.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gtzvfaourg.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtwgifpowz.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtwzcjyjux.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtsqvkwoxw.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtgodpoagx.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtgapzehwh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtgmfdmwpb.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gteyxmonns.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gtltarqeiv.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtcrgtsxmn.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtovhqsdht.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtzuckcsqn.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfckhhvmv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtpusmnnuv.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtuucfmsvq.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtjboioqzn.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtyvglqigw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtpujgxkdm.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtklaoxhgi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtumqbrpvn.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gtjxszbhrh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtgmxcegqf.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtkxxfrvke.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtcgndndyj.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtqgfbhidw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gteiipsrry.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gtzjivujat.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtfajaonnn.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqbwjeuy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gtqlzvcroi.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtigrqiiyn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gttevewpyh.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtcegzbxoy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtigkoavdm.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gtmmkfkwfs.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtavjzklqh.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtavpnjbih.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtutukbmpa.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtvoorldxe.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxyckoslu.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtnlqdxued.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gtiplgfdes.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gtwwhszieh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtghpmuqli.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gticavfghm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbeviyacu.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtgymlnfwm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtpsfojyux.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtxegffkcf.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtnzqzhjqy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtzzacfifl.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtewvmaenh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbbgmsks.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtizecpiji.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtleyewqqd.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtqpqladro.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtscxdbezk.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtxdwwdixp.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gtgpoqpfsz.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gtlxmjekmy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtrwtmfmxg.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtmkxnxdyo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtyybxwnon.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtubzxykrw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtleimiveg.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtqbytfytt.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtgbevkskf.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtkqbpeika.html


<!-- 参考信息 -->