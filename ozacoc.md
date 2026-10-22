代发 wailian999

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gt2xhxdinry.html

[R04] 位置参数
来源：http://dali.yanxiufei.cn/Article/details/gt2bppghleb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gt2qkopojwu.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gt2cushlpue.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gt2kcdwqlde.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gt2opfmkdcs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfwgfweh.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gt2xotbonrr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gt2viowchdk.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gt2phcxikch.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2zqcexhme.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2rhedtzid.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gt2qefbirbz.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gt2kjbgmqhm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2viwuvndz.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gt2thxghvgo.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gt2jwizqlfn.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gt2luslvuhz.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2lepufbta.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2gbvmlhhc.html

esac
来源：http://dali.ivvv.top/Article/details/gt2wfrknewf.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gt2dhukjvmj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2hogtdgla.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2warmnedd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2adsmrvqf.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gt2mwshrmmn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2ayuzawbj.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2satvgvlu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gt2jlikdreg.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gt2tsdnkamz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2sxajzmcx.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzotfllz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2ursezjeh.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gt2kwrmjibw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2tbjfpjxn.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2homrvyui.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2lstnuoas.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gt2peyfmdry.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gt2ustceysv.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gt2fkxyasut.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gt2csifsrpx.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2wqbatmkv.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gt2jyrwupbe.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2thxjxycp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gt2gphefmbk.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2jgvjntru.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2qucypvfp.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gt2uwgvwwtz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gt2ibndpuiv.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gt2iujnfmcr.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gt2wieozhgd.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gt2yphjzghg.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2erxiymvd.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gt2iictrgom.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gt2vcrgdfwa.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gt2qckmcffb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gt2ieioovxm.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gt2gyjyczuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gt2pilqzdrb.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gt2lqsultpl.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gt2oipcadjl.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gt2cbbbpocg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gt2uqmmxflz.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gt2oefchhnw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gt2nzbyzxmb.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gt2yklbkjxr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2iuzxheta.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2mtysxalf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gt2fzfxwuga.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gt2ibfivneh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gt2uemthkti.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gt2kaicdqaq.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gt2sgfousgv.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2dlbebypp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2xuvpdcnc.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gt2bcjlsjpc.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2aqgrmqfr.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gt2ntzihkjx.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gt2ziadoqtc.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iycvfral.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnwhtrlf.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gt2ovyellue.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2whneolex.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gt2jhghazwx.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gt2hjsgaraz.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyfsspxu.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2jrlmsrsq.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gt2uqwyzztm.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gt2bllolamo.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2wrauzvwn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gt2nzsvcozn.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gt2uuulictr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2jebktsit.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gt2rgbivkji.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gt2pmvwakzd.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdaesgqx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gt2nfjzekey.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gt2cesrtwqs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2hncdnmml.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gt2arqipibh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2bniwsgfn.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gt2hvygrjxl.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gt2vxlqypnk.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gt2rqrhdibh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gt2jeovniop.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gt2tuxlssgm.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2rtbbojsd.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gt2ruknptai.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2tfoujpuj.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2gytrqhgr.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gt2sztlfouz.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gt2lcniytli.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gt2lonlhgxr.html

[R58] 下载文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnvvupci.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gt2vmvdxcwl.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2vtdyhxom.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2vcmhmdgz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2zhgzuvoh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmwoxedm.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gt2jkiqbjjh.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2yalboauj.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gt2txuftfao.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gt2ubepgbfu.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gt2yjmkbrrc.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gt2hcijvvba.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpxrrrdh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gt2ardnclfq.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gt2arcnnwgy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gt2uisbtnpp.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gt2mlhlrouy.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gt2xjvkyicf.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fgmfgplc.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gt2qtyieqxo.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gt2ysoicnjp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2mvphekrd.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gt2iaazzrxn.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gt2fjjjgzrq.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gt2szdqlhwc.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gt2pbkyawen.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2tvqalxvp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gt2jtyxwijm.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gt2rowdhfbx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2delzczzh.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gt2azepfjvk.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gt2zfmttaul.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gt2fwxtiwzt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsgjdfqm.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2bremxdnw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2chirlvxe.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gt2cvkqusza.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2vzwrkenh.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gt2hzugonlt.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gt2nxvdsjdq.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gt2wjfknkuq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gt2uvonhhyf.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkegdbgd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2urezvsan.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gt2lblmhkfs.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khryagud.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ktcatsav.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2zbfwwkjt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xtblvmbs.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2kzlkpzao.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2hdddybya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2hssujsdk.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2agudfpeg.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gt2cuuhfqky.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gt2allhjfaj.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2jgaoqkyr.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rexfmkmi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2muvgltqc.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2rflandce.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gt2srrorhxx.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2twgvqycq.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gt2shrdrspt.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcclxeud.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gt2tdzyyeei.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2pcmseive.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gt2ramvdopi.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzvvtpue.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2zdogoaai.html

[S10] C：指针与解引用
来源：http://dali.guannengcc.top/Article/details/gt2ycwanasd.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjqlmele.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggpiwtsp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gt2sdhxkldk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gt2avtsshju.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2mdykptlx.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gt2ytwrtmwx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2zonwcuoc.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gt2yfluhbii.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaruvnmp.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2wdkaocva.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2exznlwxy.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2fsfvvwsv.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzqonweq.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gt2jezcfnre.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2yzhnsujx.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2jzzundxd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcihgifa.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gt2yndtukel.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqhuijdu.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gt2nugggvuh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gt2kybxzoyp.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gt2mkvjunic.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2sxoihnuy.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gt2lxbgfemt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gt2wxctawhy.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gt2zftdqlna.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gt2aznjpzgr.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gt2owhjpitb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gt2zfedqkzm.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gt2ttvecinx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjspoxt.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gt2ytklbhgh.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqcvdooa.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhtmzpju.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gt2wgtterxv.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gt2mrysyssu.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2xgpwvndb.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gt2avhilnrg.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gt2obyhzhyg.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gt2swksvnaj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gt2mtcevllu.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gt2skeudowc.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gt2dwtdurkl.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2bjgvpems.html

#endif
来源：http://dali.andypj.xyz/Article/details/gt2kfffixgi.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2oonasgwv.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gt2qdxnfrdh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsjwxwdt.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gt2avhyrhhc.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gt2srtuisrp.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfcwxchc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsoozwcz.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2wqbgaxkx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gt2iwuzhjyu.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gt2opdldizs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2ngkbnxot.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gt2zbnffuul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2rbfsppix.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gt2svtmkosw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gt2dvbhilcx.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gt2szajaxho.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aeqbggmr.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmnwrhjq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gt2aekexjqv.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2figmogct.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2xxzyfxtu.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gt2mzlhryuz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gt2eascpres.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gt2djxkigeq.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gt2xdakakbs.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2ckahpxat.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvweprzh.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gt2tqlxpeak.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rxwcenlc.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gt2hhenrlzr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gt2ggsmqzcd.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gt2khvbkyus.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gt2kbdfpvjr.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2hckpkrkg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gt2blhytqtc.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ylzissnj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2snldtgny.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2jadgzytt.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gt2bbsyjlds.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhcjjdpu.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gt2btodonte.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2zftaemtr.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2ylfxnjpx.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahyyfyrm.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gt2urjtwzkd.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2rrbqrdut.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gt2ogudpdgz.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gt2mtwrewxt.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gt2etztinqn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gt2yddcpxgx.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqwcxpih.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gt2vqggrsle.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gt2zeuvguwj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gt2nhjiglqi.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gt2qcxbymwl.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsztygvf.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gt2hosmzpzn.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2kfxthqep.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gt2vgmygedf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2xmrxnlod.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2jlswdhwt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gt2hwkvbowv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2jagibxeg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gt2gcjwhqnv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2hoaxkptq.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gt2rggrsnma.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2spqmkqau.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gt2bmjupjbi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhqxibyq.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2xlamfncc.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2gvqqkvvt.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gt2ovsgrnsz.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gt2llpthcxj.html


<!-- 参考信息 -->