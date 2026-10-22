代发 wailian999

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gt2ukebktqv.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2vgjofqov.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2dkhdyuoz.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trgktvtl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2gwttudyg.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gt2tkixgsai.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gt2jmnohcnq.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2opfccnta.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gt2oczfbqyi.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gt2owqkrzao.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gt2neyxffzz.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gt2fxvhdoki.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gt2xmirxgrw.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gt2cuayvcve.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyzxnzgg.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2bifdxuop.html

esac
来源：http://dali.nwbrower.top/Article/details/gt2oljxjier.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gt2fxsaxfyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gt2gnrjiucr.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gt2aaznyjkh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gt2msypcibw.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2zpglwyub.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2mwqtlcyc.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2jqweetpk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gt2xdgmjfyu.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gt2fhmrfoxl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gt2zvllzohp.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gt2adpnryei.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngtetptv.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gt2hzzhknpm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gt2ifnwvmbw.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2lafkvvue.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gt2jrgotdfe.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gt2whmecsbd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gt2dfdhwzku.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2dliabqtl.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gt2ztvgapjy.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2bqqcdroh.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gt2ihqhxptt.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oencvpvk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gt2ldklmvrz.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oshlxwpv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2mjwtmrts.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gt2iamneude.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gt2cnhfogpg.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gt2ojsbhrwa.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gt2syituphc.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gt2bbhuvoal.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gt2lwsvhfwt.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2ghmulpen.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gt2ghkekunk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pragatcd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2adrhjisj.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoudspjs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2fizhpwxn.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gt2qssljlnq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gvtqjjgt.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gt2aroqvmhw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2isokpjtd.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gt2ofvpceve.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2csoaviht.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gt2wevdgmjo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2jvvjhmvi.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2rpujupwq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gt2tszjtzuj.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2lxsghzub.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gt2gaoyfyyq.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2mrfkkrvk.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqszyvps.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gt2mnrqtvit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gt2fviyvcbi.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gt2hmnuimnz.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2rxhxwvrs.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gt2ezjfgfaz.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gt2zedkvglt.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gt2qjqajqtk.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gt2qfcghzlt.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gt2miduqjjv.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2xwfcjukn.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2rotmacvs.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gt2wraypglv.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gt2nmdphsev.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gt2wkqgkrvq.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gt2foajsezg.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yenplfxn.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2iqrgdmly.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tncxebgn.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2lhwgszae.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2ptlymyth.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2kmcodfzd.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2knczxkuv.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gt2ldklqzfp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2enqlmxwd.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gt2hnphwptc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2dtwagafd.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gt2bgsepxyr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2rzfowbjc.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gt2cniwaklc.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gt2uzickilk.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gt2fhtzojck.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gt2jizcoijy.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkvhjrbh.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jttuhkfa.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gt2hnyecnxn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gt2qqjevlbd.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2aovzwbqt.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2irbnlnjv.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gt2kyljtnkb.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2dlarvatl.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2jskfhnli.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjnvehfo.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2mljaobwx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gt2vdvmtykg.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2emdryvpu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gt2jofogmww.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2plouphpz.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2hbjdrlop.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gt2hggatlyo.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gt2mfeepkzr.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gt2aptvjfdl.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gt2ywvemonp.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imyuvouv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gt2qqrkbooq.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gt2mgpnkfzz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gt2dagoqyxu.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gt2giiafjli.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2posicvdo.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gt2hvnlrben.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gt2uoaxuavd.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2rpfliieb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2sjkefawf.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gt2xmetdizy.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2twzdreta.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgsvggmf.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gt2hgalaozs.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2scaczjhr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gt2fnvoopfr.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gt2gntrfysn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2ygjlabli.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gt2oebymawa.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esairmna.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gt2mqdaepsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gt2tsyrkcyj.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gt2rsvvvgrr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gt2ndfhfrwy.html

[R76] 使用临时文件
来源：http://dali.jiagoushi.top/Article/details/gt2lzbculop.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2mvyoiptd.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2epmltros.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gt2tptevnyg.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfytdbeg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gt2ehnuihep.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibymubbh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gt2qlkqlesf.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gt2ijmxjyfx.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gt2gqjxcipv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bcznautd.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gt2yonqqwka.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2mcryaljq.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2cilaapeg.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2krvwrkjj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzxfupuo.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gt2tdibtyrt.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vehxxzkw.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggpelxpd.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnjwjzdj.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gt2dgjivbgi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2dwnfyrwn.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2oumekkkr.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gt2baysanxv.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2ltfzislf.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gt2bmbipbux.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gt2qqoczwgf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gt2uznsmgsi.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gt2napoikdy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gt2rrwsqbiw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gt2lwsgrltu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gt2doazunrw.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gt2swnbjcme.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gt2hemgacun.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2nbmhutsl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gt2iuntgbiu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2vktwyhau.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2mkvrynxm.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2llgzukmn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdpfoexd.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2kyuijwqu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gt2mnwzaxqg.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2atflmfmw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohetydcw.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gt2wrnfogtj.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gt2floavgot.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gt2beicgdpj.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gt2egkqlaku.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2mngpkzbx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gt2yhgnshkm.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2chbyumom.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfysivnx.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gt2bufmqnrx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2aymzcqvs.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gt2yzkfpbhz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2pmgogyhg.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2regixdne.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gt2lfbzsdmj.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gt2zbiexbhf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gt2jskjxocj.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gt2bglbulrq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2kwflrjqf.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gt2nfdosvjy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gt2czaplnsj.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2taelsyra.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gt2hgevriek.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gt2azqrhxqf.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2glalhjyu.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2hwelexvi.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2nledpyjj.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2slradbww.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gt2kparwfao.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gt2ymomtkqu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gt2xplcsfrx.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gt2dznmanlb.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxystoxd.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gt2epqxgoey.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2yzboxpgh.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2ilcimawd.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2jsmvidio.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2ynvncbie.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gt2jlvgbtur.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gt2dwtwwfdt.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gt2qpdlvyuv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gt2efxqffvk.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gt2zrqighdm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gt2pqofpews.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2fjlcltrx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2kqewdjav.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gt2lxsynuql.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2yirmlfvc.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gt2qddozsfe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2votflxkl.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2lbkxwpws.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gt2ziazqamm.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gt2dvdcjnoc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gt2igyykuzd.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gt2qjdkbjec.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gt2yiwhufsb.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2xwhgytam.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2entddngk.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2larckevj.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2atwugbwu.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gt2togzupcd.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2xnuzlskc.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gt2mmsmwhpq.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2avitcute.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gt2leaxjrkz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gt2zozpwpgk.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gt2tcmlpced.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2utrnmwwm.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gt2gdgjlshe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fvilucpb.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqyjzdak.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gt2dvqhgosd.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gt2ngtphaft.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2qsojqhsa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gt2ddgcfkcw.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmvutvfo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2hshwyetf.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2fizebqhw.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gt2mafnqwsh.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gt2vbiqsmnz.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2lbabgjty.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gt2lidulknq.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzomvwbt.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gt2xhqfpkxf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gt2obfwpliy.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gt2jyovdszx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gt2hiezlcma.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gt2ntwsfagg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gt2xpskgpan.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gt2mappfdmv.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2ufiueivw.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gt2nkvkokte.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gt2rgmkeinu.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2agjcnkoc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gt2loniyllk.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gt2acskadyy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwxbnrnn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ckvvuowk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gt2esmsknby.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2veesswgo.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2eieqovjc.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2tkcrmlbi.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gt2npitdgos.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gt2msbslniw.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gt2fruyqvdc.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2cgwacjen.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gt2licxhqla.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gt2heizrzvd.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gt2iwjffswf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdekiuzz.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gt2udkpyonu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2ouuvpoyg.html


<!-- 参考信息 -->